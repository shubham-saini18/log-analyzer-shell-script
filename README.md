# 📊 Log Analyzer and Report Generator

Hello there! 👋

Welcome to the Log Analyzer and Report Generator! If you’re a system administrator or a DevOps enthusiast, you know how vital log files are for maintaining healthy systems. This handy Bash script is here to make your life easier by automating the tedious process of log analysis. Let’s dive in!

## What’s Inside? 🛠️

### Features You’ll Love
- **Automatic Log Analysis:** Forget the manual digging; this script does the heavy lifting for you.
- **Error Counting:** Quickly spot how many errors are lurking in your logs.
- **Critical Event Alerts:** Don’t miss out on those important alerts—this script highlights critical issues.
- **Daily Summary Reports:** Get a clear and concise report of your findings to share with your team.
- **Neat Log Archiving:** Keeps your log directory tidy by moving processed logs to an archive.

## Let’s Get Started! 🚀

### Prerequisites
Before we jump in, make sure you have:
- Bash (version 4.0 or higher)
- Basic Linux command-line tools like grep, awk, and sort

### Installation Steps
1. **Clone the Repository:** Get your hands on the code!
   ```bash
   git clone https://github.com/yourusername/log-analyzer.git
   cd log-analyzer
   ```

2. **Make It Executable:** Give it the green light to run!
   ```bash
   chmod +x log_analyzer.sh
   ```

### How to Use It
Ready to roll? Here’s how to run the script:
```bash
./log_analyzer.sh /path/to/your_log_file.log
```
Replace `/path/to/your_log_file.log` with the path to your log file.

### Example Execution
Run the script like this:
```bash
./log_analyzer.sh sample_log.log
```

## How Does It Work? 🤔
Here’s a quick peek under the hood:
- **Input Validation:** Checks if you’ve provided a valid log file path.
- **Log Processing:** Uses grep to find and count error messages while highlighting critical events.
- **Report Generation:** Outputs a summary report for you to review and share.
- **Log Archiving:** Automatically moves the processed log file to an `archived_logs/` directory—keeping things tidy!

## Want to Make It Better? 🤗
Here are some ideas for enhancements you might consider:
- **Email Notifications:** Why not get alerts directly in your inbox for critical events?
- **Support for Multiple Logs:** Analyze several log files at once—perfect for busy sysadmins!
- **Custom Error Keywords:** Let users define their own keywords for a tailored experience.

## Join the Party! 🎉
Contributions are what make open-source projects shine! If you’d like to help out, here’s how:
1. **Fork the Repo:** Click that shiny fork button!
2. **Create a Branch:** `git checkout -b feature/your-feature`
3. **Make Your Changes:** Add something awesome!
4. **Commit Your Changes:** `git commit -m 'Add some feature'`
5. **Push to Your Branch:** `git push origin feature/your-feature`
6. **Open a Pull Request:** Let’s review your hard work together!

## License
This project is open-source. Feel free to use and modify it to your heart's content!

## Let’s Connect! 💬
I’d love to hear from you! If you have questions, feedback, or just want to say hi, reach out via GitHub Issues or drop me an email at sainishubham416@gmail.com.
