# 🧠 MiniLoRA - Learn to tune medical language models

[![](https://img.shields.io/badge/Download-Release_Page-blue.svg)](https://github.com/Abinash8068/MiniLoRA/releases)

MiniLoRA provides a way to train small language models on medical text. This project focuses on the Qwen2.5-0.5B model. It helps users teach a computer to understand medical terminology without requiring massive hardware. You can adjust the behavior of the model using a process called Low-Rank Adaptation, or LoRA. This makes the model specialized for health-related questions.

## 📋 System requirements

You need a Windows computer to run this software. Ensure your system meets these standards:

- Operating System: Windows 10 or Windows 11 (64-bit).
- Processor: An Intel Core i5 or AMD Ryzen 5 or better.
- Memory: At least 16 GB of RAM.
- Graphics: An NVIDIA GPU with at least 8 GB of VRAM. This is important for fast training.
- Storage: At least 10 GB of free space on your hard drive.

## 📥 How to download

Follow these steps to get the software files:

1. Visit the project release page: [https://github.com/Abinash8068/MiniLoRA/releases](https://github.com/Abinash8068/MiniLoRA/releases).
2. Look for the latest release version at the top of the list.
3. Click the link that says "Assets" to show the available files.
4. Download the file ending in .zip to your computer.
5. Create a new folder on your desktop.
6. Open the .zip file and move all documents into that folder.

## ⚙️ Setting up the software

Before you start, you must install the necessary components for the software to work.

1. Install Python from the official website. Ensure you check the box that says "Add Python to PATH" during installation.
2. Open the command prompt on your computer. You can find this by typing "cmd" in the Windows search bar.
3. Type the command `cd` followed by a space, then drag the folder you created into the command window. Press Enter.
4. Run the setup script provided in the folder. Type `pip install -r requirements.txt` and press Enter. 
5. Wait for the computer to download the necessary pieces. This may take a few minutes depending on your internet speed.

## 🚀 Running your first training

Once you finish the setup, you are ready to train the model.

1. Open the command prompt inside your project folder as you did before.
2. Prepare your medical text data. Place your text files in the folder named "data".
3. Start the process by typing `python main.py` in the command prompt.
4. The program will now load the Qwen2.5-0.5B model. It will read your text data and begin the fine-tuning process.
5. You will see progress bars on your screen. Do not close the window while these bars move.
6. When the process finishes, the software will save a "LoRA adapter" file in the "output" folder.

## 💡 Understanding the results

The LoRA adapter is a small file that changes how the base model thinks. You can use this file to load your custom medical assistant. If the answers are not what you expect, check your data files. High-quality data leads to better model accuracy. Remove spelling errors from your input text before training. This improves the performance of the final model.

## 🔧 Frequently asked questions

**What if the program crashes?**
Most crashes happen due to low memory. Close all web browsers and background programs before you start the training process.

**Can I stop the training early?**
Yes. Press Ctrl+C in the command prompt to stop the process. The program will save whatever progress it made up to that point.

**Where does the model go?**
The program keeps everything in your root folder. You will find log files, configuration settings, and your trained adapters in the subfolders.

**Is my data private?**
Yes. The software runs entirely on your local machine. No data leaves your computer during the training process. You maintain full control over your information. 

**What is Qwen2.5-0.5B?**
This is a small, efficient language model. It is designed to work well on consumer hardware while keeping enough intelligence to handle complex tasks like medical summarization or terminology explanation.

**Do I need a GPU?**
While you can run the software on a standard processor, a GPU with dedicated memory makes the training much faster. Without a good GPU, the process will take significantly longer.

**How do I improve results?**
Add more medical examples to your data folder. Ensure your data has a consistent format. The more consistent your examples, the more reliably the model follows your instructions. 

This project provides a foundation for your medical language tasks. Take your time to organize your data, check your system resources, and follow the steps above to build your own assistant.