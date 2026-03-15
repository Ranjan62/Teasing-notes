# Interactive Teasing Notes Webpage 😏

A playful interactive webpage built using **HTML, CSS, and JavaScript** where teasing note cards appear one-by-one and the user can submit answers.
Responses are sent directly to your email using **Web3Forms**.

---

# Features

* Clean **Red & White theme**
* Floating **animated hearts background**
* **Start button** to begin interaction
* Notes appear **one-by-one with animation**
* Each note has:

  * Question text
  * Input box
  * Send Answer button
* Responses are sent to **email via Web3Forms**
* **Mobile responsive design**
* Entire project runs in **one HTML file**

---

# Project Structure

This project intentionally keeps everything simple.

```
project-folder
│
└── index.html
```

All code is inside one file:

* HTML → Page structure
* CSS → Styling and animations
* JavaScript → Interaction logic

---

# How It Works

1. User opens the webpage.
2. A **Start 😏** button appears.
3. When clicked:

   * Button disappears
   * Note cards appear one-by-one.
4. Each card contains:

   * A teasing message
   * Input field
   * Send Answer button.
5. When user submits an answer:

   * The response is sent to **Web3Forms**
   * The answer arrives in your **email inbox**.

---

# Setup Instructions

## 1. Download the project

Save the file as:

```
index.html
```

---

## 2. Get Web3Forms Access Key

Go to:

```
https://web3forms.com
```

Enter your email and generate an **Access Key**.

---

## 3. Replace Access Key

Inside the HTML file find this line:

```
<input type="hidden" name="access_key" value="YOUR_ACCESS_KEY">
```

Replace it with your key:

```
<input type="hidden" name="access_key" value="YOUR_KEY_HERE">
```

Example:

```
value="8ab2c9c4-xxxx-xxxx-xxxx"
```

---

## 4. Run the Project

Simply open:

```
index.html
```

in any browser.

No server required.

---

# Customizing the Notes

Inside the JavaScript section you will see a **notes array**:

```
const notes = [
{
id:1,
text:"Question here",
placeholder:"Suggested reply"
}
]
```

You can modify:

* `text` → The teasing question
* `placeholder` → Suggested answer hint

---

# Technologies Used

* HTML5
* CSS3
* JavaScript
* Web3Forms (form backend)

---

# Mobile Support

The page is responsive and works on:

* Desktop
* Mobile
* Tablets

---

# Future Improvements (Optional)

Possible upgrades:

* Typing animation for notes
* Save responses in database
* Show final message after all answers
* Add sound effects
* Deploy online and share link

---

# License

Free to use and modify.

