# CTk Quote Generator

A modern and minimal quote generator application built with **Python**, **CustomTkinter**, and the **Quotable API**, featuring theme switching, a clean UI and fast quote retrieval.


## ✨ Features

- 🎨 **Modern UI** using CustomTkinter  
- 🔄 **Light/Dark theme toggle**  
- 🎲 **Random theme color** each time the app starts  
- 📝 **Fetch inspirational quotes** using the Quotable API  
- 🔗 Clickable API link (opens in browser)  
- 📋 **Right-click menu** (Copy, Paste, Cut)  
- 🖥 **Cross-platform** (Windows, Linux, macOS)  
- ⚡ Fast, lightweight, beginner-friendly codebase  


## 🖼 Preview

Here are some screenshots of the `CTk Quote Generator` project:

**Main Page with Dark Mode**<br/>
![Main Page](screenshots/main_1.png)<br/>
**Output Page with Light Mode**<br/>
![Output Page](screenshots/main_2.png)


## 🛠 Technologies Used

- **Python 3.11+**  
- **CustomTkinter**  
- **Requests**  
- **Tkinter**  
- **Quotable.io API**


## 📦 Installation

### 1. Clone the Repository  
```bash
git clone https://github.com/iamx-ariful-islam/CTk-Quote-Generator.git
cd CTk-Quote-Generator
```

### 2. Install Dependencies

Make sure `pip` is available in your system PATH.

```bash
pip install -r requirements.txt
# or (Linux/MacOS)
sudo pip install -r requirements.txt
```
The `requirements.txt` file, lists of all the python libraries that my "**_CTk Quote Generator_**" depends on and installs those packages from the file.

### 3. Run the Application
```bash
python main.py
```


## 📁 Project Structure
Here’s the structure of the **CTk Quote Generator** project:

```bash
CTk-Quote-Generator/
│
│── screenshots/
│── main.py
│── LICENSE
├── README.md
└── requirements.txt
```


## 🌐 API Used
This project uses the Quotable API:
**`https://api.quotable.io/random`**


## 💡 How It Works

1. Click Generate Quote → The app calls the Quotable API
1. The app parses the JSON response
1. The quote and author are displayed in the text box
1. Users can copy/paste text via right-click menu
1. Appearance can be toggled between Light/Dark


## 🔧 Customization
### Change default random theme
Inside `main.py`:

```bash
ctk.set_default_color_theme(random.choice(['blue', 'green', 'dark-blue']))
```
You can add more themes or set a static theme.


## 🤝 Contributing

Contributions, suggestions, and feedback are always welcome! ❤️<br/>
To contribute:

1. Fork the repository
2. Create a new branch (`feature/new-feature`)
3. Commit your changes
4. Push and submit a Pull Request

💬 You can also open an issue if you’d like to discuss a feature or report a bug.


## 🌐 For more or connect with me

<p align='center'>
  <a href="https://github.com/iamx-ariful-islam"><img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white" /></a>&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://x.com/mx_ariful_islam"><img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" /></a>&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://bd.linkedin.com/in/iamx-ariful-islam"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>&nbsp;&nbsp;&nbsp;&nbsp;
  <a href="https://www.facebook.com/jonakisoft.net/"><img src="https://img.shields.io/badge/Facebook-%231877F2.svg?style=for-the-badge&logo=Facebook&logoColor=white" /></a>&nbsp;&nbsp;&nbsp;&nbsp;
</p>


## 📜 License

The [MIT](https://choosealicense.com/licenses/mit/) License (MIT)


## 💖 Thank You for Visiting!

> “Good design is about making things simple yet significant”  
> — *Md. Ariful Islam*