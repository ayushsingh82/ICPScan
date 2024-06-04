# ICPScan

## Introduction

ICPScan is a tool designed to simplify the tracking of transactions and balances within the Icp domain. ICPScan aims to provide a one-stop solution for tracking addresses, balances, internal transactions, and external transactions. We have connected .eth to .icp through ICNS (Interchain naming system) https://app.icns.xyz/

# Features

- **Address Tracking**: Easily track addresses within the Icp domain.
- **Balance Monitoring**: Keep an eye on the balance of addresses.
- **Internal Transaction Tracking**: Monitor internal transactions within the Icp domain.
- **External Transaction Tracking**: Track external transactions involving Icp domain addresses.
- **Comprehensive Portfolio Overview**: ICPScan provides a comprehensive overview of your Icp domain portfolio, including detailed information such as time, hash, and more.
- **Future Development**: The future goal of ICPScan is to evolve into a complete portfolio tracker for ICP. This will include additional features such as portfolio performance analysis, asset allocation insights, and customizable reporting.

![image](https://github.com/ayushsingh82/ICPScan/assets/121667116/64078c17-21fe-4c37-8bbb-b3c3d03bcb66)



# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh


We are using The-Graph protcol for fetching the ens domain address.
After getting the ens domain address we are using etherscan to fetch the balance of user , internal transactions and normal transactions of user.
