<div align="center">
  <img src="https://grow.empress.eco/uploads/default/original/2X/1/1f1e1044d3864269d2a613577edb9763890422ab.png" alt="Nextcloud Integration Logo">
  <p>Automated, comprehensive, and customizable backup solution for your database, config, and files to Nextcloud. 
  <br /> 
  <a href="https://empress.eco/">Explore the Docs</a>
  ·
  <a href="https://github.com/empress-eco/nextcloud/issues">Report Bug</a>
  ·
  <a href="https://github.com/empress-eco/nextcloud/issues/new?assignees=&labels=&template=feature_request.md&title=">Request Feature</a>
  </p>
</div>

## About The Project

Nextcloud Integration is a full-featured backup solution tailored for developers and businesses. It ensures secure, automated, and flexible backups of your database, configuration, and files to your Nextcloud instance, providing an added layer of security for your precious data.

### 🌟 Key Features
- **Automated backups**: Choose between daily or weekly schedules for your backups.
- **Comprehensive scope**: Back up your database, configuration, and files all at once.
- **Email notifications**: Stay informed about successful backups or get alerted when they fail.
- **Customizable backup location**: Choose where on your Nextcloud instance you want your backups to be stored.

## Technical Stack and Setup Instructions

### Prerequisites
To use Nextcloud Integration, you need a running Nextcloud account and a site where you can install the *nextcloud-integration* app.

### Installation
Clone the repository and install the Nextcloud Integration app using the following commands:

```sh
git clone https://github.com/empress-eco/nextcloud.git
bench get-app nextcloud_integration
bench --site {site_name} install-app nextcloud_integration
```

After successful installation, search for **Nextcloud Settings** in the **Awesome Bar** to configure the backup settings as per your requirement.

## Usage

Using Nextcloud Integration is straightforward. After installing and configuring the app, click on the **Backup Now** button. The backup process usually takes a few minutes to half an hour, depending on the size of your backup.

## Contribution Guidelines

We welcome contributions from the community. Here's how you can contribute:

1. **Fork the Project**: Create a copy of the project in your GitHub account.
2. **Create a Feature Branch**: Create a new branch (git checkout -b feature/AmazingFeature).
3. **Commit Your Changes**: Make changes and commit them (git commit -m 'Add some AmazingFeature').
4. **Push to the Branch**: Push your changes to the branch (git push origin feature/AmazingFeature).
5. **Open a Pull Request**: Create a new pull request from your forked repository.

## License and Acknowledgements

### License
This project is licensed under the MIT License. Your contributions are also licensed under this same License.

### Acknowledgements
We express our profound gratitude to the Empress Community for their foundational contributions. Their innovative tools and dedicated support have played a crucial role in building this project. We are also thankful to the team at [Empress](https://empress.eco/) for creating this useful tool and to the open-source community for their invaluable contributions.