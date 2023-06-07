const readmeEnglish = `

![imgAlejandro (1)](https://github.com/Bangarrett/Bangarrett/assets/126791771/15b400ff-845f-4db6-b0f3-955d254e8cc9)


## About Me

Hello, I'm Alejandro Calquin, a passionate software developer with a love for technology and visual effects. I enjoy combining creativity and code to create stunning visual experiences.

## Featured Projects

Here are some of my featured projects along with a brief description for each. You can click on the links to access the corresponding repositories.

${createProjectLink('path/to/image1.png', 'Project 1', 'An interactive website with stunning visual effects, designed to provide an immersive experience to users.')}
${createProjectLink('path/to/image2.png', 'Project 2', 'A mobile application that combines augmented reality and visual effects to create a unique product visualization experience.')}
${createProjectLink('path/to/image3.png', 'Project 3', 'A real-time visual effects library implemented using cutting-edge technologies like WebGL and shaders.')}

## Skills

Throughout my career, I have acquired skills in various areas of software development and technology. Here's a list of some of my key skills:

${createSkillsList(['JavaScript', 'PHP', 'React', 'Laravel', 'Node.js', 'MySQL', 'MongoDB', 'Git', 'VS Code'])}

## Contribution

If you're interested in collaborating on any of my projects or have any ideas we can work on together, feel free to contact me. I'm open to new opportunities and love working as part of a team.

## Contact

You can find me on the following platforms:

- **Email**: acalquinpenna@email.com
- **LinkedIn**: [linkedin.com/in/alejandro-calquin-penna-8b6866273/](https://www.linkedin.com/in/alejandro-calquin-penna-8b6866273/)
`;

const readmeSpanish = `
# Alejandro Calquin



Breve descripción sobre mí y mis intereses.

## Sobre mí

Hola, soy Alejandro Calquin, un apasionado desarrollador de software con una pasión por la tecnología y los efectos visuales. Me encanta combinar la creatividad y el código para crear experiencias visuales sorprendentes.

## Proyectos destacados

Aquí te presento algunos de mis proyectos destacados junto con una breve descripción de cada uno. Puedes hacer clic en los enlaces para acceder a los repositorios correspondientes.

${createProjectLink('ruta/a/imagen1.png', 'Proyecto 1', 'Un sitio web interactivo con efectos visuales impresionantes, diseñado para proporcionar una experiencia inmersiva a los usuarios.')}
${createProjectLink('ruta/a/imagen2.png', 'Proyecto 2', 'Una aplicación móvil que combina realidad aumentada y efectos visuales para crear una experiencia única en la visualización de productos.')}
${createProjectLink('ruta/a/imagen3.png', 'Proyecto 3', 'Una biblioteca de efectos visuales en tiempo real, implementada utilizando tecnologías de vanguardia como WebGL y shaders.')}

## Habilidades

A lo largo de mi carrera, he adquirido habilidades en diversas áreas de desarrollo de software y tecnología. Aquí hay una lista de algunas de mis habilidades clave:

${createSkillsList(['JavaScript', 'PHP', 'React', 'Laravel', 'Node.js', 'MySQL', 'MongoDB', 'Git', 'VS Code'])}

## Contribución

Si estás interesado en colaborar en alguno de mis proyectos o tienes alguna idea en la que podamos trabajar juntos, no dudes en contactarme. Estoy abierto a nuevas oportunidades y me encanta trabajar en equipo.

## Contacto

Puedes encontrarme en las siguientes plataformas:

- **Email**: acalquinpenna@email.com
- **LinkedIn**: [linkedin.com/in/alejandro-calquin-penna-8b6866273/](https://www.linkedin.com/in/alejandro-calquin-penna-8b6866273/)
`;

const combinedReadme = readmeEnglish + "\n\n" + readmeSpanish;

console.log(combinedReadme);
