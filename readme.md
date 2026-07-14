# 📧 Email Automation with ChatGPT

A Python-based email automation tool that integrates **IMAP (Internet Message Access Protocol)** with **OpenAI's ChatGPT** to automatically process incoming emails and generate intelligent content such as blogs, news articles, summaries, social media posts, or any custom output based on your prompt.

This project enables you to monitor selected email accounts, read unseen emails, extract their content, and let ChatGPT perform customized tasks automatically.

---

# 🚀 Features

* ✒️ **Automatic Content Generation**

  * Generate blogs, news articles, reports, or social media posts from newly received emails.

* 🤖 **AI-Powered Email Processing**

  * Ask ChatGPT to perform custom tasks using the email content.

* 📬 **Read Unseen Emails**

  * Fetch unread emails directly from your mailbox using IMAP.

* 📊 **Complete Email Metadata Access**

  * Email Subject
  * Sender Information
  * Email Body
  * Received Time
  * Sender Count

* ⚙️ **Highly Customizable**

  * Configure prompts, number of emails to process, output length, and target email senders.

---

# 🛠️ Requirements

Before using this project, ensure the following requirements are completed:

### 1. Enable 2-Step Verification

Enable 2-Step Verification for your Google Account.

### 2. Generate an App Password

Create a Google App Password and use it instead of your regular Gmail password.

> **Note:** Never share or commit your App Password to GitHub.

### 3. Enable IMAP

In Gmail:

**Settings → See all settings → Forwarding and POP/IMAP → Enable IMAP**

---

# 📥 Input Parameters

| Parameter     | Description                                 | Default                |
| ------------- | ------------------------------------------- | ---------------------- |
| `how_many`    | Number of unread emails to process          | `10`                   |
| `maxtoken`    | Maximum length of the generated response    | `200`                  |
| `what_to_ask` | Prompt sent to ChatGPT                      | `"Write a blog about"` |
| `num_target`  | Number of target email addresses to monitor | `None`                 |

---

# 💡 Example Use Cases

* 📰 Convert newsletters into blog posts
* 📢 Create social media content from emails
* 📝 Summarize long email threads
* 📚 Generate meeting notes
* 📈 Produce business reports
* 🔍 Extract important information automatically
* 💼 Automate email-based workflows

---

# ⚙️ Workflow

```text
Incoming Email
        │
        ▼
Read Unseen Emails via IMAP
        │
        ▼
Extract Email Content
        │
        ▼
Send Prompt + Email Body to ChatGPT
        │
        ▼
Generate Custom Output
        │
        ▼
Blog / News / Summary / Post / Report
```

---

# 📂 Project Structure

```text
Email-Automation/
│
├── main.py
├── config.py
├── requirements.txt
├── README.md
└── ...
```

---

# 🔒 Security Notes

* Never expose your Gmail App Password.
* Add sensitive credentials to a `.env` file or environment variables.
* Avoid committing secrets to public repositories.
* Rotate your App Password if it is ever exposed.

---

# 🤝 Contributing

Contributions are welcome!

To contribute:

1. Fork the repository.
2. Create a new branch for your feature or bug fix.

```bash
git checkout -b feature/my-feature
```

3. Commit your changes.

```bash
git commit -m "Add new feature"
```

4. Push your branch.

```bash
git push origin feature/my-feature
```

5. Open a Pull Request.

If you add a new application:

* Create a separate project folder.
* Include a dedicated `README.md`.
* Update the main repository `README.md`.

---

# 👨‍💻 Author

**Md. Karaamathullah**

*Data Scientist*

---

# ⭐ Support

If you find this project useful, consider giving it a ⭐ on GitHub. Your support helps improve the project and encourages future development.
