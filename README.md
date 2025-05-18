<div align="center">
    <img src="https://www.getmonero.org/img/monero-logo.png" alt="Monero Logo" width="200">
</div>

# XMRig Dashboard APP

XMRig Dashboard is a monitoring tool for miners using XMRig. This project provides a simple and intuitive interface with charts and reports on mining performance, pool connectivity, and detailed device information. The interface is powered by the XMRig API and displays essential data such as hashrate, shares, and pool status.

# 📊 Features

- Hashrate Monitoring: Track your miner's performance in real time.
- Device Stats & Temperature: View device data including temperature and hashrate.
- Graphical Reports: Visualize performance over time with interactive charts.
- Pool Connectivity: Check the status of your mining pools with connection details.

# 🖥️ Web Interface

The interface displays the following information:

- Hashrate
- Shares
- Device Temperature (If OS has this information)
- Pool Status

Data is updated in real-time, and interactive charts help you monitor mining performance.

# 🔧 How to Run the Project

- Clone the repository:
  ```bash
  git clone https://github.com/leonardorifeli/xmrig-dashboard-app.git
  cd xmrig-dashboard-app
  ```
- Replace the Bearer Token:
  Open the main.go file and replace YOUR_BEARER_TOKEN with your actual authentication token.
- Install Go (if necessary):
  If you don't have Go installed, follow the instructions here: Install Go.
- Run the server:
  ```bash
  go run main.go
  ```
- Access the Web Interface:
  Open your browser and go to http://localhost:3000 to view the dashboard.

# 🧑‍💻 Contributing

- Fork the repository.
- Create a branch (git checkout -b feature-branch-name).
- Make your changes and commit them (git commit -am 'Add new feature').
- Push to the repository (git push origin feature-branch-name).
- Open a pull request.

# 💖 Sponsorship

If you appreciate this project and would like to support its continued development, please consider sponsoring me through [GitHub Sponsors](https://github.com/sponsors/leonardorifeli).

Your contributions help improve the project and enable me to spend more time maintaining and adding new features.

![Sponsor me on GitHub](https://img.shields.io/badge/Sponsor%20me%20on-GitHub-brightgreen?logo=github)

# 📄 License

This project is licensed under the [MIT License](https://leonardorifeli.mit-license.org/) - see the [LICENSE](https://github.com/leonardorifeli/xmrig-dashboard-app/blob/main/LICENSE) file for details.