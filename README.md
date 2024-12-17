# Greenkeeper 🌱  
### Automated Dependency Updates for npm Projects  

> **Important Announcement:**  
> Greenkeeper will sunset and transition to **Snyk** on **June 3rd, 2020**. New installations are no longer possible.  
> 🚀 **[Learn how to migrate to Snyk here.](https://greenkeeper.io)**  

---

<div align="center">
  <img src="https://user-images.githubusercontent.com/391124/36849148-8a73f484-1d63-11e8-8f2b-d7ffa940cb31.jpg" alt="Greenkeeper" />
</div>

<p align="center">
  <a href="https://greenkeeper.io/"><img src="https://badges.greenkeeper.io/greenkeeperio/greenkeeper.svg" alt="Greenkeeper"></a>
  <a href="https://travis-ci.org/greenkeeperio/greenkeeper"><img src="https://travis-ci.org/greenkeeperio/greenkeeper.svg?branch=master" alt="Build Status"></a>
  <a href="https://david-dm.org/greenkeeperio/greenkeeper/master"><img src="https://david-dm.org/greenkeeperio/greenkeeper/master.svg" alt="Dependency Status"></a>
  <a href="https://greenkeeper-slack.herokuapp.com/"><img src="https://greenkeeper-slack.herokuapp.com/badge.svg" alt="Slack"></a>
  <a href="https://github.com/semantic-release/semantic-release"><img src="https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg" alt="Semantic Release"></a>
</p>

---

## 🚀 What is Greenkeeper?

Greenkeeper automates dependency updates in npm projects. By integrating with your CI pipeline, it identifies breaking changes **before they impact production**.  

Key features:  
- **Real-time updates**: Automatically test dependency updates in branches.  
- **Actionable Issues**: Provides clear, actionable insights on breaking updates.  
- **Works with CI**: Supports tools like Travis CI, CircleCI, and Jenkins.  

---

## 🌍 Who Uses Greenkeeper?

Over **10,000 projects** trust Greenkeeper, including:  
- [Lodash](https://lodash.com)  
- [PouchDB](https://pouchdb.com/)  
- [Google AMP](https://github.com/ampproject/amphtml)  
- [Modernizr](https://modernizr.com)  
- [FreeCodeCamp](https://freecodecamp.org)  
- and many more!  

---

## 🛠 How It Works  

Greenkeeper sits between npm and GitHub, watching your dependencies:  

1. **Update Triggered**: A dependency gets updated on npm.  
2. **Branch Creation**: Greenkeeper creates a new branch with the update.  
3. **CI Testing**: Your CI system tests the changes automatically.  
4. **Feedback**: You receive an issue with results:  
   - ✅ **Passing**: Safe to merge.  
   - ❌ **Failing**: Greenkeeper suggests pinning the last working version.  

**Example:**  

| **Pinning Dependencies** |  
| --- |  
| ![Pin Example](https://cdn-images-1.medium.com/max/1600/0*T11jS2wNKlbQVbgC.) |  

---

## 📝 Core Job Documentation  

The Greenkeeper **Jobs Service** handles dependency updates, CI integration, and issue creation. Below is a summary of job types:  

| Job Type                     | Description                                                   |  
| ---------------------------- | ------------------------------------------------------------- |  
| `github-event`               | Handles GitHub webhooks (e.g., `push`, `pull_request`).       |  
| `registry-change`            | Detects updates in npm and creates version branches.          |  
| `create-pin-branch`          | Pins a dependency to the last working version.                |  
| `create-version-branch`      | Creates branches for updated dependencies.                    |  
| `close-issue`                | Closes an issue when a dependency passes CI tests.            |  
| `delete-branches`            | Cleans up unused or older dependency branches.                |  

For a more in-depth breakdown of job types, see the [full documentation](#jobs-service-documentation).  

---

## 🤝 Contributing  

We welcome contributions! Check out our:  
- [Contributing Guide](https://github.com/greenkeeperio/greenkeeper/blob/master/CONTRIBUTING.md)  
- [Code of Conduct](https://greenkeeper.io)  

---

## 🔒 Security  

If you discover a security vulnerability, **please report it confidentially**:  
📧 **support@greenkeeper.io**  

**DO NOT** disclose security issues publicly (e.g., GitHub Issues).  

---

## 📚 Additional Resources  

- [📘 FAQ](https://greenkeeper.io/faq.html)  
- [📝 Blog](https://blog.greenkeeper.io/)  
- [📄 General Documentation](https://greenkeeper.io/docs.html)  

---

### 💚 Thank You for Trusting Greenkeeper!  

For continued dependency security and automation, please migrate to **Snyk** before June 3rd, 2020.  
👉 **[Learn how to migrate here.](https://greenkeeper.io)**  

---

Feel free to tweak this as needed! It maintains professionalism, clarity, and better structure for readers.
