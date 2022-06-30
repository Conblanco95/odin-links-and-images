# odin-links-and-images
Repo for the Foundations Links and Images assignment

---

## Links Notes:
1. Absolute Links: links to pages on **other websites on the internet**. This link consists of the following --> `protocol://domain/path` which in practice looks like `https://www.theodinproject.com/about`
2. Relative Links: links to other pages on **our own website are relative**. The assumption is the domain will remain the same so it is not included in the link, and the link will include just the file path to the other page *relative* to the page you're creating the link on.

## Images Notes:
* Image links are self closing tabs and look like `<img src="https://www.theodinproject.com/mstile-310x310.png">`
1. For **absolute paths**, the element would look like the one above.
2. For **relative paths**, the **src=""** would look like `src="images/dog.jpg"`.

---

## Knowledge Check
* What element is used to create a link?
  * `<a href=""></a>`
* What is an attribute?
  * An **HTML attribute** gives additional information to an element in the opening tag. It's made up of two parts; **name**, **value**. It looks like `name="value"`.
* What attribute tells links where to go to?
  * `href=""`
* What is the difference between an absolute and relative link?
  * **Absolute** links are links to pages on other websites on the internet. **Relative** links are links to pages on our own websites.
* Which element is used to display an image?
  * `<img src="" alt="">`
* What two attributes do images always need to have?
  * `src=""` points towards the absolute or relative path, `alt=""` is used for describing the image and accessibility.
* How do you access a parent directory in a filepath?
  * Use the `../` to theoretically step back out of the room into the *hallway* then step into the room of your choosing from where you currently are in the file system.
* What are the four main image formats that you can use for images on the web?
  * JPG, GIF, PNG, SVG
