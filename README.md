```javascript
// Bienvenue sur mon GitHub 🚀

const christianNelles = {
    greeting: "ET BAH BIEN LE BONJOUR ! 👋",
    aboutMe: {
        description: "Développeur apprentis, je partage ici mes projets et mes réalisations.",
        currentlyWorkingOn: [
            "Création de sites web",
            "Intelligence artificielle",
            "Jeux vidéos"
        ],
        lookingForHelpWith: "Trouver une alternance",
        contact: "Vous pouvez me joindre via les liens ci-dessous 👇"
    },
    links: {
        linkedin: "https://www.linkedin.com/in/christian-nelles-1b89a2338/",
        youtube: "https://www.youtube.com/channel/UC_DGS2GugVKRuNgnyvJCyzQ"
    },
    skills: [
        "JavaScript",
        "HTML",
        "CSS",
        "Python",
        "PHP",
        "C++"
    ]
};

// Affichage des informations (comme dans une console 😉)
console.log(christianNelles.greeting);
console.log("À propos de moi :", christianNelles.aboutMe.description);
console.log("Actuellement, je travaille sur :", christianNelles.aboutMe.currentlyWorkingOn.join(", "));
console.log("Je recherche de l'aide pour :", christianNelles.aboutMe.lookingForHelpWith);
console.log("Liens :");
Object.entries(christianNelles.links).forEach(([platform, link]) => {
    console.log(`- ${platform}: ${link}`);
});
console.log("Compétences :", christianNelles.skills.join(", "));
