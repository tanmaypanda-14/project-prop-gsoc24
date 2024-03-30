# Electron Forge Documentation Migration to Docusaurus

## Personal Details

- **Name:** Tanmay Panda
- **University:** Maharashtra Institute of Technology, Pune
- **Degree:** Bachelor of Technology (B.Tech)
- **Email:** [tanmaypanda](mailto:tanmay404103@outlook.com) (connect with me on [LinkedIn](https://www.linkedin.com/in/tanmay1404/))
- **Portfolio:** [tanmaypanda.vercel.app](https://tanmaypanda.vercel.app)
- **GitHub:** [tanmaypanda-14](https://github.com/tanmaypanda-14)
- **Telephone:** +91 823 787 9806
- **Country of Residence:** India
- **Timezone:** IST (GMT + 0530)
- **Primary Language:** English

I am a third-year undergraduate student pursuing a Bachelor of Technology degree in Computer Science and Engineering. I have a keen interest in open-source software development and have contributed to various projects on GitHub. I am proficient in JavaScript, React, Node.js, and have experience working with Javascript-based Frameworks and Libraries. I am excited about the opportunity to work on the Electron Forge documentation migration project and contribute to the Electron community.

If selected for this project, I am committed to dedicating the required time and effort to ensure the successful completion of the project within the stipulated timeline. I can put in approximately 30-35 hours per week on this project and am open to discussions, feedback, and collaboration with the Electron team and the project mentor. If needed, I am willing to adjust my schedule to accommodate meetings, reviews, and other project-related activities. I m completely flexible with the project timeline and can adjust my schedule as per the project requirements.

## Project Abstract

The project aims to migrate the existing Electron Forge documentation from GitBook to Docusaurus, aligning it with the core Electron documentation setup. This migration will improve documentation management, accessibility, and user experience for developers working with Electron Forge.

## Why I chose this project?

I chose this project with the sole intention of getting to know the people of the open-source community and to contribute to the Electron project. As a developer, I understand the importance of well-structured and accessible documentation. I believe that migrating the Electron Forge documentation to Docusaurus will enhance the user experience and make it easier for developers to work with Electron Forge. I am excited about the opportunity to work on this project and contribute to the Electron community.

This would be my gateway to the electron community. Post this project i would like to pick up more challenging tasks and contribute to the electron project.

## Technical Skills

| **Frontend**  | **Backend** | **Version Control** | **Project Management** | **DevOps**     |
| ------------- | ----------- | ------------------- | ---------------------- | -------------- |
| React         | Node.js     | Git                 | Jira                   | Docker         |
| Next.js       | Prisma      | BitBucket           | Trello                 | AWS            |
| Tailwind      | MongoDB     | CodeCommit          | Github Projects        | Github Actions |
| Redux         | Express     |                     |                        |                |
| GraphQL       | PostgreSQL  |                     |                        |                |
| Apollo        | Python      |                     |                        |                |
| Framer Motion | Django      |                     |                        |                |

## Proposed Project Flow
### May 27 - July 12: Initial Setup and Content Migration

- **May 27 - June 12 (3 weeks):**
  - Familiarize with Electron Forge documentation structure and Docusaurus setup.
  - Set up Docusaurus documentation site for Electron Forge.
  - Begin migrating existing documentation content to Docusaurus.

- **June 13 - June 26 (2 weeks):**
  - Continue migrating documentation content, focusing on content accuracy and formatting.
  - Configure navigation, sidebar, and overall layout based on Electron's documentation guidelines.

- **June 27 - July 12 (2 weeks):**
  - Customize Docusaurus theme to align with Electron branding and color palette.
  - Configure navigation menus, sidebar structure, and page hierarchy for optimal user experience.

### July 12 - August 26: Plugin Integration, Testing, and Documentation

- **July 12 - July 18 (1 week):**
  - Develop and integrate a plugin to import and display TypeDoc API documentation for Electron Forge.
  - Test plugin functionality and ensure seamless integration with Docusaurus site.

- **July 19 - August 1 (2 weeks):**
  - Implement dynamic rendering of API documentation pages using the plugin.
  - Review and refine API documentation content and structure for clarity and completeness.

- **August 2 - August 8 (1 week):**
  - Implement versioning support for Electron Forge documentation using Docusaurus.
  - Set up search functionality powered by Algolia for quick and efficient content search.

- **August 9 - August 15 (1 week):**
  - Integrate internationalization (i18n) support for multilingual documentation.
  - Customize Docusaurus components, styles, and layouts as per Electron's design guidelines.

- **August 16 - August 26 (1 week):**
  - Prepare for deployment of the updated Electron Forge documentation.
  - Compile comprehensive documentation for the Docusaurus setup, customization, and plugin integration.
  - Write guidelines and instructions for maintaining and updating the Electron Forge documentation on Docusaurus.

## How Docusaurus works

### Overview
Docusaurus is a static site generator designed to simplify the process of building, deploying, and maintaining documentation websites.

1. **Architecture**:
   - Docusaurus is built on top of React, allowing for a component-based structure that promotes reusability and maintainability.
   - It uses Markdown and MDX (Markdown with embedded JSX) for content creation, making it easy for non-technical users to write and update documentation.
   - The core functionality is provided by plugins and themes, which can be customized to suit specific project requirements.(this will help us make it consistent with electron's branding and color pallete)

2. **Key Features**:
   - **Markdown Support**: Docusaurus supports Markdown for creating content pages, blog posts, and API documentation.
   - **Versioning**: It offers versioning support, allowing you to maintain multiple versions of documentation and switch between them seamlessly.
   ![Docusaurus Architecture](https://i.imgur.com/EfQDFcr.png)
   - **Search Functionality**: Docusaurus includes a built-in search feature powered by Algolia, making it easy for users to find relevant information quickly.
   ![search](https://i.imgur.com/ngtLutb.png)
   - **Internationalization (i18n)**: It supports internationalization, enabling you to create multilingual documentation sites.
   ![i18n](https://i.imgur.com/FiDnXej.png)
   - **Customization**: Docusaurus provides extensive customization options through themes, plugins, and configuration files, allowing you to tailor the look and feel of your documentation site.
   ![custom](https://i.imgur.com/Gdcwprl.png)
   - **Deployment**: It supports various deployment options, including static site hosting platforms like Netlify, Vercel, GitHub Pages, and custom servers.

3. **Workflow**:
   - **Setup**: To start a Docusaurus project, you typically use the Docusaurus CLI (`@docusaurus/init`) to create a new project with a predefined folder structure and configuration files.
   - **Content Creation**: You write documentation content in Markdown or MDX format and organize it into pages, blog posts, and documentation sections.
   - **Configuration**: Docusaurus provides a `docusaurus.config.js` file where you can configure site metadata, navigation menus, plugins, themes, and other settings.
   - **Development**: During development, you use the Docusaurus development server (`pnpm start`) to preview your site locally and make changes.
   - **Build**: When ready to deploy, you run the build command (`pnpm run build`), which generates a static version of your site in the `build` directory.
   - **Deployment**: Finally, you deploy the built static files to your chosen hosting platform, ensuring that the documentation site is accessible to users.

4. **Performance and Scalability**:
   - Being a static site generator, Docusaurus produces highly optimized static HTML, CSS, and JavaScript files, resulting in fast page load times and improved performance.
   - It scales well for large documentation projects, thanks to its versioning support, search functionality, and customizable navigation structures.

In summary, Docusaurus simplifies the process of creating and maintaining documentation websites by providing a developer-friendly architecture, key features like Markdown support and versioning, extensive customization options, and a supportive community ecosystem.

## Plugin for TypeDoc and Docusaurus integration

While searching for possible solutions to migrate the Typedoc documentation of the Electron Forge API to Docusaurus, I came across an open-source project called [typedoc-plugin-markdown](https://github.com/tgreyuk/typedoc-plugin-markdown). Typedoc utilizes frontmatter and generates type-based documentation that is class-specific based on decorators and param comments. The author of this repository has used the same frontmatter utilities to create a template that outputs files in Markdown format. However, upon reviewing the code, I noticed that the author has not made the plugin compatible with the latest versions of Typedoc.

Additionally, the same author has a Docusaurus plugin, [docusaurus-plugin-typedoc](https://github.com/tgreyuk/typedoc-plugin-markdown/tree/master/packages/docusaurus-plugin-typedoc#readme), which directly takes TypeScript source files and places them into the `docs/api` folder as documentation. The only issue is that the author only supports version 2 of Docusaurus, which is deprecated and unoptimized. We should stick to version 3.2 of [Docusaurus](https://docusaurus.io/blog/releases/3.2) as it offers better build times and more customization options.

```
    ├── docs/
        ├── api/ (compiled typedoc markdown)
        ├── gitbook content 
    ├── docusaurus.config.js
    ├── package.json
    ├── sidebars.js
├──package.json
├──src (electron-forge api  source)
├──tsconfig.json
```
As seen in the above folder structure we will set the entry point to the index of the electron-forge api and our plugin will create documentation for it.

Under the guidance of mentors from the Electron team, I propose to either update the support version of the mentioned plugin or create a new plugin from scratch with improved support for Docusaurus.

## Conclusion

I am excited about the opportunity to work on the Electron Forge documentation migration project and contribute to the Electron community. I am confident in my technical skills and ability to deliver high-quality work within the stipulated timeline. I am looking forward to collaborating with the Electron team, the project mentor, and the community to ensure the successful completion of the project. Thank you for considering my proposal, and I am eager to contribute to the Electron project.

> **Note:** My main focus is to develop the `TypeDoc API documentation plugin` for Electron Forge in the Docusaurus site. The video above is a representation of the work done so far and I am confident that i can complete the original project( migration of the gitbook docs to docusaurus) well before the stipulated timeline. Post the completion of the original project, I would like to work on the plugin development and integration, for which i will require mentorship from the Electron team.
