# dio-create-ebook-with-AI

Ebook generated with AI

Note: this is a repository created during the Santander bootcamp offered at DIO that integrates the labs developed during the course. 
In the original project, ChatGPT, Midjourney, and PowerPoint were used to create an ebook on CSS with a geek theme. In this version, 
an ebook for learning English with the shadowing method will be created, including a brief description of this method and 10 texts with 
links to the corresponding media.

For this version, PowerPoint will be replaced by HTML and CSS, which will be entirely created using the code generation functionality of ChatGPT. 
Then, the single-page created with all the content will be printed to PDF for finalization of the material. This option is due to the flexibility and 
proficiency of HTML and CSS in text formatting and styling, proving to be, in my view, a more suitable tool for ebook creation. Additionally, it allows 
for better exploration of ChatGPT as not only the content creator but also the formatter.

The media for each text consists of AI-generated audio created through Murf.ai. As this is a paid tool, only the ebook will be included for this project, 
but it will remain open for future commits, replacing Murf with some free tool that allows audio generation to complete the material.


Tecnologias utilizadas:

- [ChatGPT](https://openai.com/gpt): Para geração de texto e formatação.
- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML) e [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS): Para criação e estilização de páginas web.
- [Murf.ai](https://murf.ai/): Para geração de áudio através de inteligência artificial.

Creating the content with ChatGPT：

|   Action   | prompt                                                                                                                                                                                                                                                                         |
| :------: | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
|  title  | Create the title for an ebook that serves as a guide to practicing English with shadowing. Include in the title something that motivates people to approach learning languages as a means to explore the world. |
| preface | Create a text 30 lines long about the shodowing technique for learning languages. The text should be a preface to an ebook that will contain texts and audios to be used with this technique)|
| instructions | Create a text 30 lines long about What is shadowing|
| content | Create a text 30 lines long to be used in learning English. The text should be at an intermediate level. Use the subject [subject] ([subject] here should be repalced with the subjecct as many times as texts that will go into the ebook)|


Formatting the ebook with ChatGPT:

The contenct should be organized in one file that will be submitted to ChatGPT with the following prompt:

- Create a web page in HTML and CSS with the text below, making it look like an ebook.

Creating the cover:

I used ChatGPT to make a simple cover that could be way more alaborated using image generators, but for the sake of this projext, I'll stick with plane HTML + CSS.

- I'm going to print this HTML page to PDF and use it as a book cover. You need to create a cover art using CSS and HTML. It's not a website. It's an actual book cover, and it should be in the format of an A4 page, including the title [title], the author [author], and other typical cover elements. Also, please add some CSS art to the cover, something that enhances its visual appeal. Remember that I will print an A4 page to PDF afterward.

