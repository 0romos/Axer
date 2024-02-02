
<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/0romos/Axer">
    <img src="https://media.discordapp.net/attachments/1202805721696313385/1202805776041771088/AxerLog.png?ex=65cecb2c&is=65bc562c&hm=472e1e487e1d794bab35ad8df0bc93ecd1c36120592e1345c3dc5cedb29851e8&=&format=webp&quality=lossless&width=675&height=675" alt="Logo" width="100" height="100">
  </a>

  <h3 align="center">Axer</h3>

  <p align="center">
    Exploit faster with simplicity and ease
    <br />
    <a href="https://github.com/0romos/Axer"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/0romos/Axer/">View Demo</a>
    ·
    <a href="https://github.com/0romos/Axer/issues">Report Bug</a>
    ·
    <a href="https://github.com/0romos/Axer/issues">Request Feature</a>
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about">About The Project</a>
    </li>
    <li>
      <a href="#installation">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#usage">Usage</a></li>
      </ul>
    </li>
    <li><a href="#features">Features</a></li>
    <li><a href="#customexploits">Custom Exploits</a></li>
    <li><a href="#contributing">Contributing</a></li>
  </ol>
</details>

<br />
<center> <h1 align="left" id="about">About</h1> </center>

Axer is a straightforward yet effective Python-based framework tailored to simplify the process of working with digital exploits. This lightweight program is designed to offer users a user-friendly and accessible approach to managing and deploying exploits, catering to both novice and experienced users.

![image](https://github.com/0romos/Axer/assets/138330732/545c407d-1a38-4779-a402-079828b762a6)



Axer is your passport to a customized exploit framework, enhancing the capabilities of your Banner Project Repository. Remember, ethical and responsible use of such tools is paramount. Ensure they are harnessed only for authorized and legitimate security testing purposes.

<br />
<center> <h1 align="left" id="installation">Installation</h1> </center>

_Below is an example of how you can instruct your audience on installing and setting up your binary file. This template doesn't rely on any external services._

1. Clone the repo

   ```sh
   git clone https://github.com/0romos/Axer.git
    ```

<br />
<center> <h1 align="left" id="usage">Usage</h1> </center>

1. Run Axer

   ```sh
    $ cd Axer && python3 main.py
    ```

   ```sh
    $ python3 main.py
    ```
   
See the [open issues](https://github.com/0romos/Axer) for a full list of proposed features (and known issues).

<br />
<center> <h1 align="left" id="features">Features</h1> </center>

### Key Features of Axer Exploit Framework:

- **Automated Exploit Loading:** Axer streamlines the process of loading exploits, saving you time and effort.
  
- **Customizability:** Tailor Axer to your preferences and project needs. Make it an integral part of your workflow.

- **Speed and Efficiency:** Axer's automated capabilities ensure quick and efficient exploit deployment.
  
- **Custom Command Naming:** Personalize exploit commands to align with your project's conventions.
  
- **Modular Exploit Storage:** Store, organize, and manage your preferred exploits with ease.
  
- **Detailed Descriptions:** Each exploit comes with customizable descriptions for clarity and context.
  
- **Fine-Tuned Matching:** Specify criteria for exploit selection, ensuring precise vulnerability targeting.
  
- **Version Management:** Stay up-to-date with the latest exploit versions, enhancing project security.
  
- **Customizable Appearance:** Tailor Axer's visuals to seamlessly blend with your project's branding and aesthetics.
  
- **Comprehensive Documentation:** Axer generates detailed reports and logs for thorough project documentation.

These features collectively make Axer a versatile and valuable addition to your project repository, enhancing your security testing efforts while promoting responsible and ethical use of exploit tools.

PS: Some are not added yet!

<br />
<center> <h1 align="left" id="customexploits">Custom Exploits</h1> </center>

You can also load custom exploits of your choice! This is the Default template inside of `exploits` folder filaname.py:

```py
from core.modular import Module

class Exploit(Module):

    def __init__(self):
        """
        Initialize an Exploit object with default attributes.

        The attributes 'name', 'description', 'author', and 'creation_date' are initialized
        with example values for demonstration purposes.

        self.name should be the same as the file name.

        You can create more functions and call them inside of Execute same goes for classes.
        """
        self.name           = "commandname"
        self.description    = "Example description of this exploit."
        self.author         = "Username"
        self.creation_date  = "00-00-1337"

    def execute(self):
        """
        Placeholder method for the exploit's execution logic.

        Subclasses of Exploit must override this method to define the specific behavior
        of the exploit when executed. This method may return data or perform actions.
        """
```

<br />
<center> <h1 align="left" id="contributing">Contributing</h1> </center>

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b new-dev-20220608`)
3. Commit your Changes (`git commit -m 'Added Language Support'`)
4. Push to the Branch (`git push origin new-dev-20220608`)
5. Open a Pull Request


<!-- LICENSE -->
<br />
<center> <h1 align="left" id="license">License</h1> </center>

Distributed under the MIT License. See `LICENSE` for more information.
    
