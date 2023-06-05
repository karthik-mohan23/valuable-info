1.  What does <!DOCTYPE html> specify?
    Ans => The <!DOCTYPE html> declaration is used at the beginning of an HTML document to tell web browsers which version of HTML the document is written in. It stands for "Document Type Declaration" and it specifically indicates that the document is written in HTML5.

---

2.  So what does <html lang="en"> specify ?
    Ans => This attribute helps search engines and assistive technologies (such as screen readers) identify and understand the language of the document. It also allows browsers to apply language-specific rules for rendering, such as text direction or hyphenation.

---

3.  Why <head> is used ?
    Ans => The <head> element is an essential part of an HTML document. It is used to define metadata and provide instructions to the web browser about various aspects of the document. Here are some common elements typically included within the <head> section:

<title>: This tag specifies the title of the document, which appears in the browser's title bar or tab.

<meta>: This tag is used to provide additional information about the document, such as the character encoding, viewport settings, keywords, description, and author.

<link>: This tag is used to include external resources such as CSS stylesheets or icon files.

<script>: This tag is used to include or reference JavaScript files or scripts.

<style>: This tag is used to embed CSS styles directly within the HTML document.

------------------------------------------------

4. What does charset="UTF-8" do ?

Ans => The charset="UTF-8" attribute/value pair is typically included within the <meta> tag in the <head> section of an HTML document. It specifies the character encoding for the document, specifically using the UTF-8 encoding.

Character encoding determines how characters are represented and stored in a computer's memory. UTF-8 (Unicode Transformation Format-8) is a widely used character encoding scheme that can represent almost all characters from all writing systems in the world.

Including charset="UTF-8" in the <meta> tag informs the browser that the document is encoded using UTF-8. This ensures that the browser interprets and displays the text content of the HTML document correctly, regardless of the language or special characters used.

UTF-8 is recommended as the standard character encoding for web documents because it supports a wide range of characters, including those from different languages, symbols, and emojis. It helps prevent encoding issues and ensures proper rendering of text across different browsers and operating systems.

------------------------------------------------

charset(character set) => Think of the "charset" as a set of rules or instructions that tell the computer which code to use for each symbol. When we specify the "charset" in an HTML document, we are telling the computer how to read and display the symbols on a webpage. It ensures that the correct symbols are shown, and everything looks as intended. Without the proper charset, the computer might get confused and display strange characters or question marks instead of the intended symbols.

------------------------------------------------

Encoding is like a secret code that computers use to understand and store information. Just like how we use different languages to communicate, computers have their own language, which is a series of 0s and 1s called binary code.

When we encode something, we convert it into this binary code. It's like translating information into the computer's language. For example, when we type a letter on a keyboard, the computer encodes it into binary code before storing or processing it.

Encoding helps ensure that information can be properly stored, transmitted, and understood by computers. It's like putting information into a format that computers can easily work with. And when we want to see or use that information again, the computer decodes it back into a readable form for us.

So, encoding is essentially the process of converting information into the computer's language, allowing it to be stored, sent, and processed effectively.

------------------------------------------------

5. http-equiv="X-UA-Compatible" content="IE=edge" explain this line of code.

Ans => The http-equiv="X-UA-Compatible" attribute is used within the <meta> tag in the <head> section of an HTML document. It provides instructions to the browser on how to handle or render the webpage.

In simpler words, this code tells the browser how to behave when it encounters the HTML document. It specifically deals with compatibility issues between different versions of Internet Explorer (a web browser).

The X-UA-Compatible value is set to specify a specific document mode or compatibility mode for Internet Explorer. By setting it to a particular version or mode, you can ensure that the webpage is displayed correctly and consistently in Internet Explorer.

For example, http-equiv="X-UA-Compatible" content="IE=edge" instructs Internet Explorer to use the latest available rendering engine, ensuring optimal compatibility and performance.

This attribute is often used to address compatibility issues in older versions of Internet Explorer, making sure that the webpage is viewed properly and functions as intended across different versions of the browser.

------------------------------------------------

6. What does name="viewport" content="width=device-width, initial-scale=1.0" this line do ?

Ans => They provide instructions to the browser on how to adjust the webpage's dimensions and scaling for different devices.

In simpler terms, these instructions help the webpage look good and be user-friendly on various screen sizes, such as smartphones, tablets, or desktop computers.

The width=device-width part tells the browser to set the width of the webpage to be equal to the width of the device's screen. This ensures that the webpage adapts to the specific device it is being viewed on, preventing horizontal scrolling or content getting cut off.

The initial-scale=1.0 part sets the initial zoom level of the webpage. A value of 1.0 means the webpage is displayed at its original size without any zooming in or out by default.

By including these instructions, the webpage can be responsive and adjust its layout and scaling appropriately, providing a better user experience across different devices and screen sizes.

------------------------------------------------

7. body tag

Ans => The <body> tag is used to define the main content area of an HTML document. It represents the visible content that appears on a webpage.

In simple terms, the <body> tag contains all the elements and information that you want to display on your webpage. It includes text, images, videos, links, and other interactive elements that users can see and interact with.

When you write HTML code within the <body> tags, the content you specify will be rendered by web browsers and displayed as the actual webpage. Everything you see on a website, such as paragraphs, headings, lists, and images, is typically placed within the <body> tags.

The <body> tag essentially encapsulates the visible part of your webpage, defining its structure and content. It is where you put the elements that make up the main body of your website, making it the essential part of your HTML document.

------------------------------------------------

8.<link rel="stylesheet" href="style.css"> Explain this line of code.
Ans => Let's break down the <link rel="stylesheet" href="style.css"> code:

<link>: This is an HTML tag used to define a link between the current HTML document and an external resource, such as a CSS file.

rel="stylesheet": The rel attribute specifies the relationship between the current HTML document and the linked resource. In this case, stylesheet indicates that the linked resource is a CSS file, which is used to style the HTML document.

href="style.css": The href attribute specifies the location or URL of the external resource. Here, style.css is the file name of the CSS file you want to link to the HTML document.

In simpler terms, the <link rel="stylesheet" href="style.css"> code is used to connect your HTML document with a separate CSS file called "style.css". The CSS file contains styling instructions that control the appearance, layout, and design of your webpage.

By linking the CSS file using this code, you can keep your styling separate from the HTML document itself. This separation allows you to modify and update the visual aspects of your webpage by editing the CSS file, without changing the actual HTML structure 

------------------------------------------------

9. what is the difference between <style></style> and <link rel="stylesheet" href="style.css"> ?

Ans => The main difference is that with <style></style>, the CSS code is embedded within the HTML document, while <link rel="stylesheet" href="style.css"> refers to an external file that holds the CSS code. Using an external CSS file provides more flexibility, reusability, and ease of maintenance, especially for larger projects with multiple webpages.

---

10. The script tag ?
    Ans => src="": The src attribute specifies the source or location of an external JavaScript file that you want to include. You need to provide the file path or URL within the quotation marks.

It's important to note that the src attribute is used to reference an external JavaScript file, while the JavaScript code written directly within the <script></script> tags is called inline JavaScript. Both approaches have their use cases, depending on the complexity and organization of your code.

In summary, the <script src=""></script> code lets you include JavaScript code either inline within the HTML document or by linking to an external JavaScript file, enabling you to add functionality and interactivity to your webpage.
