# CosmoCraft: Chain Creation Guide

Welcome to the CosmoCraft, your comprehensive solution for creating Cosmos blockchains with unparalleled customization and ease. This guide will walk you through the initial steps to create your Cosmos blockchain using our intuitive UI tool, highlighting the customizations available at your fingertips.

## Getting Started

Creating a Cosmos blockchain is a seamless process with CosmoCraft. Start by accessing our UI tool, which guides you through each step, ensuring you can customize your chain according to your specific needs.

### Step 1: Chain Basics

- **Chain Name**: Give your blockchain a unique identity. This name will be used to identify your chain across the Cosmos network.
- **Bech32 Prefix**: This prefix is crucial for generating addresses on your blockchain. Choose a prefix that reflects your chain's identity.
- **Binary Name**: Define the executable name of your blockchain's node software. This name will be used when running your nodes.
- **Denomination**: Specify the token denomination for your blockchain's native currency. This will be used in transactions and balances.
- **Validator Count**: Decide on the number of validators you want to start with. This is crucial for your chain's consensus and security.

### Step 2: Modules Selection

CosmoCraft's strength lies in its modular architecture, allowing you to pick and choose the functionality your blockchain requires.

#### Default Modules

Your chain will come equipped with essential modules that form the backbone of most Cosmos blockchains:

- **Staking**: Essential for any Proof of Stake (PoS) blockchain, allowing token holders to stake their tokens as collateral to validate transactions.
- **NFT**: Supports the creation and management of Non-Fungible Tokens (NFTs), enabling a wide range of use cases from digital art to certification.

#### Interested Modules

Enhance your blockchain's capabilities by selecting from an array of available modules:

- **Proof of Authority (PoA)**: Ideal for permissioned networks where validators are known entities.
- **TokenFactory**: Create and manage multiple tokens within your blockchain ecosystem.
- **GlobalFee**: Implement network-wide transaction fees, adjustable according to your governance model.
- **IBC-PacketForward**: Leverage the Inter-Blockchain Communication protocol for cross-chain interactions.
- **CosmWasm**: Introduce smart contracts into your chain, written in Rust, facilitating complex on-chain logic.
- **Wasm-Light-Client**: Enable light clients of other blockchains to verify your chain's state, crucial for cross-chain services.
- **Ignite CLI**: Utilize this powerful command-line interface to streamline your development and deployment processes.

### Step 3: Submission

Once you've tailored your chain's settings to your liking, submit your configuration through our UI. Our backend processes these configurations and kickstarts the generation of your new Cosmos chain.


# CosmoCraft: Deployment Guide

After creating your custom Cosmos blockchain with CosmoCraft, the next critical step is deploying your chain. This guide provides a detailed overview of the deployment process, including options for CI/CD, cloud support, validator management, security considerations, testnet setup, and automated testing.

## Continuous Integration and Deployment (CI/CD)

CosmoCraft integrates a robust CI/CD pipeline, automating the build, test, and deployment phases of your blockchain. This ensures that your chain is always up to date with the latest code changes and security patches.

### How it Works

1. **Code Pushes**: Any code pushed to the main branch of your chain's GitHub repository triggers the CI/CD pipeline.
2. **Automated Testing**: The pipeline runs a series of automated tests to ensure that new code changes do not introduce errors or vulnerabilities.
3. **Deployment**: Upon successful testing, the pipeline automatically deploys the changes to your chain, ensuring minimal downtime and seamless updates.

## Cloud Support

CosmoCraft supports deployment on various cloud platforms, giving you the flexibility to host your blockchain in the environment that best suits your needs.

### Supported Platforms

- **AWS**
- **Google Cloud Platform**
- **Azure**
- **DigitalOcean**
- And more, offering a range of options for scalability, reliability, and geographical distribution.

## Validator Management

Validators play a crucial role in the security and consensus of your Cosmos blockchain. CosmoCraft offers options for both self-managed and fully managed validators.

### Self-Managed Validators

- Ideal for teams with the technical capability to manage their infrastructure.
- Provides complete control over your validators, including hardware specifications, network configurations, and security measures.

### Fully Managed Validators

- A hassle-free option where CosmoCraft takes care of validator setup, maintenance, and monitoring.
- Ensures your validators are always online and up to date with the latest security practices.

## Security Considerations

Security is paramount in blockchain deployment. CosmoCraft incorporates several security measures:

- **Automated Security Scans**: Regularly scans your codebase and infrastructure for vulnerabilities.
- **Encryption**: All data in transit and at rest are encrypted to protect against unauthorized access.
- **Access Controls**: Implements strict access controls and authentication mechanisms to safeguard your blockchain infrastructure.

## Testnet Deployment

Before deploying your blockchain to the mainnet, CosmoCraft provides a testnet environment. This allows you to:

- **Test with Multiple Validators**: Simulate real-world conditions with multiple validators to ensure your blockchain operates as expected under various scenarios.
- **Automated Testing**: Run automated tests to validate transactions, smart contracts, and consensus mechanisms without risking real assets.

### Benefits of Testnet Deployment

- Identifies potential issues in a controlled environment.
- Allows for performance benchmarking and optimization.
- Provides a safe space for developers to interact with your blockchain.

# CosmoCraft: Feature Highlights

CosmoCraft is engineered to simplify and accelerate the blockchain development process, offering a plethora of features tailored for the creation, management, and deployment of Cosmos blockchains. Here's a deep dive into the key features that make CosmoCraft a game-changer in blockchain technology.

## 1-Minute Creation Flow

- **Quick Setup**: With CosmoCraft, setting up your blockchain is a matter of minutes. Our intuitive UI guides you through the necessary steps, from naming your chain to selecting modules, without the need for deep technical know-how.
- **Instant Feedback**: Real-time validation and feedback during the setup process ensure that you can make informed decisions quickly, streamlining the creation of your blockchain.

## Modular with 30+ Modules Support

- **Wide Range of Modules**: Choose from over 30 modules across various categories, including DeFi, governance, gaming, and more, to customize your blockchain's functionality.
- **Easy Integration**: Adding or removing modules is straightforward, allowing your blockchain to evolve with your project's needs. This modular approach ensures that you're never locked in and can adapt to the ever-changing blockchain landscape.

## Fully Managed

- **Turnkey Solution**: For those seeking a hands-off approach, our fully managed option takes care of everything from validator management to updates and security, allowing you to focus on your project's development.
- **24/7 Monitoring**: Our team monitors your blockchain around the clock, ensuring high availability and swift issue resolution.

## Transaction Bot

- **Automated Transactions**: The transaction bot facilitates automated testing and interaction with your blockchain, simulating real-world transaction loads and scenarios.
- **Customizable Scripts**: Tailor the bot's behavior to fit your testing needs, whether it's stress testing your network or ensuring smart contracts perform as expected under various conditions.

## Staking and Multi-Validator Support

- **Staking Mechanisms**: Built-in support for staking, enabling token holders to secure the network while earning rewards, essential for Proof of Stake (PoS) blockchains.
- **Scalable Validator Infrastructure**: Our platform supports multi-validator setups, ensuring your blockchain can scale securely and maintain consensus integrity as your network grows.

## Enhanced Security

- **Comprehensive Security Features**: From automated vulnerability scans to encryption and strict access controls, we've baked in multiple layers of security to protect your blockchain and its users.
- **Ongoing Security Updates**: Stay ahead of threats with regular security updates and best practices implemented directly into your blockchain infrastructure.

## Explorer and Indexer

- **Blockchain Explorer**: Gain insights into your blockchain's activity with an integrated explorer, making it easy for developers and users alike to track transactions, view blocks, and monitor network health.
- **Advanced Indexing**: The indexer compiles comprehensive data about blockchain transactions and states, facilitating complex queries and analytics, essential for dApps and services relying on your blockchain.

## Conclusion

CosmoCraft is designed to empower developers and organizations to leverage blockchain technology efficiently and securely. With its focus on ease of use, modularity, comprehensive feature set, and robust support infrastructure, CosmoCraft is your end-to-end solution for building and deploying Cosmos blockchains tailored to your unique requirements. Whether you're an experienced blockchain developer or new to the space, CosmoCraft provides the tools and support you need to bring your blockchain project to life.


## Sequence flow

![eNqNVU1z0zAQvftX7PTQSQ8dCLSlcGAKTmh7YOpJQy_E41HsTSLiSEYfKeHXs7Itx4kN9Jasdt-u9r0n32jDlLGbHMZixUSKGYRSb6SGSMkfmBoIFTLDpYBnblbVYajYwgQBS41UMMIt5rJAFaAw3OzaKXXklps7O_f_TsL7V-EIIl5gzgWeANMQ3ifhKPGhJvMrE2zpRsqtNqjK1DqW1LEm93Mu03W6YlzA-FeRS1Xn7-OJ](https://github.com/shivhg/cosmocraft/assets/8338207/03630338-5176-4c02-9cb4-fc361bdaf5f5)


![Uploading eNqNVU1z0zAQvftX7PTQSQ8dCLSlc<?xml version="1.0" encoding="us-ascii" standalone="no"?><svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" contentStyleType="text/css" height="797px" preserveAspectRatio="none" style="width:1870px;height:797px;background:#FFFFFF;" version="1.1" viewBox="0 0 1870 797" width="1870px" zoomAndPan="magnify"><defs/><g><line style="stroke:#181818;stroke-width:0.5;stroke-dasharray:5.0,5.0;" x1="43" x2="43" y1="81.2969" y2="716.4844"/><line style="stroke:#181818;stroke-width:0.5;stroke-dasharray:5.0,5.0;" x1="246" x2="246" y1="81.2969" y2="716.4844"/><line style="stroke:#181818;stroke-width:0.5;stroke-dasharray:5.0,5.0;" x1="454" x2="454" y1="81.2969" y2="716.4844"/><line style="stroke:#181818;stroke-width:0.5;stroke-dasharray:5.0,5.0;" x1="720" x2="720" y1="81.2969" y2="716.4844"/><line style="stroke:#181818;stroke-width:0.5;stroke-dasharray:5.0,5.0;" x1="979" x2="979" y1="81.2969" y2="716.4844"/><line style="stroke:#181818;stroke-width:0.5;stroke-dasharray:5.0,5.0;" x1="1191" x2="1191" y1="81.2969" y2="716.4844"/><line style="stroke:#181818;stroke-width:0.5;stroke-dasharray:5.0,5.0;" x1="1310" x2="1310" y1="81.2969" y2="716.4844"/><line style="stroke:#181818;stroke-width:0.5;stroke-dasharray:5.0,5.0;" x1="1418" x2="1418" y1="81.2969" y2="716.4844"/><line style="stroke:#181818;stroke-width:0.5;stroke-dasharray:5.0,5.0;" x1="1550" x2="1550" y1="81.2969" y2="716.4844"/><line style="stroke:#181818;stroke-width:0.5;stroke-dasharray:5.0,5.0;" x1="1710" x2="1710" y1="81.2969" y2="716.4844"/><line style="stroke:#181818;stroke-width:0.5;stroke-dasharray:5.0,5.0;" x1="1839" x2="1839" y1="81.2969" y2="716.4844"/><text fill="#000000" font-family="sans-serif" font-size="14" lengthAdjust="spacing" textLength="71" x="5" y="77.9951">Developer</text><ellipse cx="43.5" cy="13.5" fill="#E2E2F0" rx="8" ry="8" style="stroke:#181818;stroke-width:0.5;"/><path d="M43.5,21.5 L43.5,48.5 M30.5,29.5 L56.5,29.5 M43.5,48.5 L30.5,63.5 M43.5,48.5 L56.5,63.5 " fill="none" style="stroke:#181818;stroke-width:0.5;"/><text fill="#000000" font-family="sans-serif" font-size="14" lengthAdjust="spacing" textLength="71" x="5" y="728.4795">Developer</text><ellipse cx="43.5" cy="740.2813" fill="#E2E2F0" rx="8" ry="8" style="stroke:#181818;stroke-width:0.5;"/><path d="M43.5,748.2813 L43.5,775.2813 M30.5,756.2813 L56.5,756.2813 M43.5,775.2813 L30.5,790.2813 M43.5,775.2813 L56.5,790.2813 " fill="none" style="stroke:#181818;stroke-width:0.5;"/><text fill="#000000" font-family="sans-serif" font-size="14" lengthAdjust="spacing" textLength="81" x="203" y="77.9951">CosmoCraft</text><ellipse cx="246.5" cy="49" fill="#E2E2F0" rx="12" ry="12" style="stroke:#181818;stroke-width:0.5;"/><line style="stroke:#181818;stroke-width:0.5;" x1="234.5" x2="258.5" y1="63" y2="63"/><text fill="#000000" font-family="sans-serif" font-size="14" lengthAdjust="spacing" textLength="81" x="203" y="728.4795">CosmoCraft</text><ellipse cx="246.5" cy="747.7813" fill="#E2E2F0" rx="12" ry="12" style="stroke:#181818;stroke-width:0.5;"/><line style="stroke:#181818;stroke-width:0.5;" x1="234.5" x2="258.5" y1="761.7813" y2="761.7813"/><text fill="#000000" font-family="sans-serif" font-size="14" lengthAdjust="spacing" textLength="47" x="428" y="77.9951">GitHub</text><ellipse cx="454.5" cy="49" fill="#E2E2F0" rx="12" ry="12" style="stroke:#181818;stroke-width:0.5;"/><line style="stroke:#181818;stroke-width:0.5;" x1="442.5" x2="466.5" y1="63" y2="63"/><text fill="#000000" font-family="sans-serif" font-size="14" lengthAdjust="spacing" textLength="47" x="428" y="728.4795">GitHub</text><ellipse cx="454.5" cy="747.7813" fill="#E2E2F0" rx="12" ry="12" style="stroke:#181818;stroke-width:0.5;"/><line style="stroke:#181818;stroke-width:0.5;" x1="442.5" x2="466.5" y1="761.7813" y2="761.7813"/><text fill="#000000" font-family="sans-serif" font-size="14" lengthAdjust="spacing" textLength="97" x="669" y="77.9951">CI/CD Pipeline</text><ellipse cx="720.5" cy="49" fill="#E2E2F0" rx="12" ry="12" style="stroke:#181818;stroke-width:0.5;"/><line style="stroke:#181818;stroke-width:0.5;" x1="708.5" x2="732.5" y1="63" y2="63"/><text fill="#000000" font-family="sans-serif" font-size="14" lengthAdjust="spacing" textLength="97" x="669" y="728.4795">CI/CD Pipeline</text><ellipse cx="720.5" cy="747.7813" fill="#E2E2F0" rx="12" ry="12" style="stroke:#181818;stroke-width:0.5;"/><line style="stroke:#181818;stroke-width:0.5;" x1="708.5" x2="732.5" y1="761.7813" y2="761.7813"/><text fill="#000000" font-family="sans-serif" font-size="14" lengthAdjust="spacing" textLength="117" x="918" y="77.9951">Managed Cluster</text><ellipse cx="979.5" cy="49" fill="#E2E2F0" rx="12" ry="12" style="stroke:#181818;stroke-width:0.5;"/><line style="stroke:#181818;stroke-width:0.5;" x1="967.5" x2="991.5" y1="63" y2="63"/><text fill="#000000" font-family="sans-serif" font-size="14" lengthAdjust="spacing" textLength="117" x="918" y="728.4795">Managed Cluster</text><ellipse cx="979.5" cy="747.7813" fill="#E2E2F0" rx="12" ry="12" style="stroke:#181818;stroke-width:0.5;"/><line style="stroke:#181818;stroke-width:0.5;" x1="967.5" x2="991.5" y1="761.7813" y2="761.7813"/><text fill="#000000" font-family="sans-serif" font-size="14" lengthAdjust="spacing" textLength="135" x="1121" y="77.9951">Blockchain Explorer</text><ellipse cx="1191.5" cy="49" fill="#E2E2F0" rx="12" ry="12" style="stroke:#181818;stroke-width:0.5;"/><line style="stroke:#181818;stroke-width:0.5;" x1="1179.5" x2="1203.5" y1="63" y2="63"/><text fill="#000000" font-family="sans-serif" font-size="14" lengthAdjust="spacing" textLength="135" x="1121" y="728.4795">Blockchain Explorer</text><ellipse cx="1191.5" cy="747.7813" fill="#E2E2F0" rx="12" ry="12" style="stroke:#181818;stroke-width:0.5;"/><line style="stroke:#181818;stroke-width:0.5;" x1="1179.5" x2="1203.5" y1="761.7813" y2="761.7813"/><text fill="#000000" font-family="sans-serif" font-size="14" lengthAdjust="spacing" textLength="70" x="1272" y="77.9951">Endpoints</text><ellipse cx="1310" cy="49" fill="#E2E2F0" rx="12" ry="12" style="stroke:#181818;stroke-width:0.5;"/><line style="stroke:#181818;stroke-width:0.5;" x1="1298" x2="1322" y1="63" y2="63"/><text fill="#000000" font-family="sans-serif" font-size="14" lengthAdjust="spacing" textLength="70" x="1272" y="728.4795">Endpoints</text><ellipse cx="1310" cy="747.7813" fill="#E2E2F0" rx="12" ry="12" style="stroke:#181818;stroke-width:0.5;"/><line style="stroke:#181818;stroke-width:0.5;" x1="1298" x2="1322" y1="761.7813" y2="761.7813"/><text fill="#000000" font-family="sans-serif" font-size="14" lengthAdjust="spacing" textLength="115" x="1358" y="77.9951">Monitoring Tools</text><ellipse cx="1418.5" cy="49" fill="#E2E2F0" rx="12" ry="12" style="stroke:#181818;stroke-width:0.5;"/><line style="stroke:#181818;stroke-width:0.5;" x1="1406.5" x2="1430.5" y1="63" y2="63"/><text fill="#000000" font-family="sans-serif" font-size="14" lengthAdjust="spacing" textLength="115" x="1358" y="728.4795">Monitoring Tools</text><ellipse cx="1418.5" cy="747.7813" fill="#E2E2F0" rx="12" ry="12" style="stroke:#181818;stroke-width:0.5;"/><line style="stroke:#181818;stroke-width:0.5;" x1="1406.5" x2="1430.5" y1="761.7813" y2="761.7813"/><text fill="#000000" font-family="sans-serif" font-size="14" lengthAdjust="spacing" textLength="117" x="1489" y="77.9951">Security Services</text><ellipse cx="1550.5" cy="49" fill="#E2E2F0" rx="12" ry="12" style="stroke:#181818;stroke-width:0.5;"/><line style="stroke:#181818;stroke-width:0.5;" x1="1538.5" x2="1562.5" y1="63" y2="63"/><text fill="#000000" font-family="sans-serif" font-size="14" lengthAdjust="spacing" textLength="117" x="1489" y="728.4795">Security Services</text><ellipse cx="1550.5" cy="747.7813" fill="#E2E2F0" rx="12" ry="12" style="stroke:#181818;stroke-width:0.5;"/><line style="stroke:#181818;stroke-width:0.5;" x1="1538.5" x2="1562.5" y1="761.7813" y2="761.7813"/><text fill="#000000" font-family="sans-serif" font-size="14" lengthAdjust="spacing" textLength="171" x="1622" y="77.9951">Configuration Verification</text><ellipse cx="1710.5" cy="49" fill="#E2E2F0" rx="12" ry="12" style="stroke:#181818;stroke-width:0.5;"/><line style="stroke:#181818;stroke-width:0.5;" x1="1698.5" x2="1722.5" y1="63" y2="63"/><text fill="#000000" font-family="sans-serif" font-size="14" lengthAdjust="spacing" textLength="171" x="1622" y="728.4795">Configuration Verification</text><ellipse cx="1710.5" cy="747.7813" fill="#E2E2F0" rx="12" ry="12" style="stroke:#181818;stroke-width:0.5;"/><line style="stroke:#181818;stroke-width:0.5;" x1="1698.5" x2="1722.5" y1="761.7813" y2="761.7813"/><text fill="#000000" font-family="sans-serif" font-size="14" lengthAdjust="spacing" textLength="54" x="1809" y="77.9951">Testnet</text><ellipse cx="1839" cy="49" fill="#E2E2F0" rx="12" ry="12" style="stroke:#181818;stroke-width:0.5;"/><line style="stroke:#181818;stroke-width:0.5;" x1="1827" x2="1851" y1="63" y2="63"/><text fill="#000000" font-family="sans-serif" font-size="14" lengthAdjust="spacing" textLength="54" x="1809" y="728.4795">Testnet</text><ellipse cx="1839" cy="747.7813" fill="#E2E2F0" rx="12" ry="12" style="stroke:#181818;stroke-width:0.5;"/><line style="stroke:#181818;stroke-width:0.5;" x1="1827" x2="1851" y1="761.7813" y2="761.7813"/><polygon fill="#181818" points="234.5,123.5625,244.5,127.5625,234.5,131.5625,238.5,127.5625" style="stroke:#181818;stroke-width:1.0;"/><line style="stroke:#181818;stroke-width:1.0;" x1="43.5" x2="240.5" y1="127.5625" y2="127.5625"/><text fill="#000000" font-family="sans-serif" font-size="13" lengthAdjust="spacing" textLength="163" x="50.5" y="107.3638">[1] Initiate Chain Creation</text><text fill="#000000" font-family="sans-serif" font-size="13" lengthAdjust="spacing" textLength="140" x="50.5" y="122.4966">Configure Parameters</text><polygon fill="#181818" points="1698.5,152.6953,1708.5,156.6953,1698.5,160.6953,1702.5,156.6953" style="stroke:#181818;stroke-width:1.0;"/><line style="stroke:#181818;stroke-width:1.0;" x1="246.5" x2="1704.5" y1="156.6953" y2="156.6953"/><text fill="#000000" font-family="sans-serif" font-size="13" lengthAdjust="spacing" textLength="170" x="253.5" y="151.6294">[2] Validate Configurations</text><polygon fill="#181818" points="257.5,196.9609,247.5,200.9609,257.5,204.9609,253.5,200.9609" style="stroke:#181818;stroke-width:1.0;"/><line style="stroke:#181818;stroke-width:1.0;" x1="251.5" x2="1709.5" y1="200.9609" y2="200.9609"/><text fill="#000000" font-family="sans-serif" font-size="13" lengthAdjust="spacing" textLength="199" x="263.5" y="180.7622">[3] Feedback on Configurations</text><text fill="#000000" font-family="sans-serif" font-size="13" lengthAdjust="spacing" textLength="88" x="263.5" y="195.895">(if any issues)</text><polygon fill="#181818" points="442.5,241.2266,452.5,245.2266,442.5,249.2266,446.5,245.2266" style="stroke:#181818;stroke-width:1.0;"/><line style="stroke:#181818;stroke-width:1.0;" x1="246.5" x2="448.5" y1="245.2266" y2="245.2266"/><text fill="#000000" font-family="sans-serif" font-size="13" lengthAdjust="spacing" textLength="122" x="253.5" y="225.0278">[4] Generate Chain</text><text fill="#000000" font-family="sans-serif" font-size="13" lengthAdjust="spacing" textLength="164" x="253.5" y="240.1606">Push Codebase to GitHub</text><polygon fill="#181818" points="708.5,270.3594,718.5,274.3594,708.5,278.3594,712.5,274.3594" style="stroke:#181818;stroke-width:1.0;"/><line style="stroke:#181818;stroke-width:1.0;" x1="454.5" x2="714.5" y1="274.3594" y2="274.3594"/><text fill="#000000" font-family="sans-serif" font-size="13" lengthAdjust="spacing" textLength="152" x="461.5" y="269.2935">[5] Setup CI/CD Pipeline</text><polygon fill="#181818" points="1538.5,299.4922,1548.5,303.4922,1538.5,307.4922,1542.5,303.4922" style="stroke:#181818;stroke-width:1.0;"/><line style="stroke:#181818;stroke-width:1.0;" x1="720.5" x2="1544.5" y1="303.4922" y2="303.4922"/><text fill="#000000" font-family="sans-serif" font-size="13" lengthAdjust="spacing" textLength="179" x="727.5" y="298.4263">[6] Perform Security Checks</text><polygon fill="#181818" points="731.5,328.625,721.5,332.625,731.5,336.625,727.5,332.625" style="stroke:#181818;stroke-width:1.0;"/><line style="stroke:#181818;stroke-width:1.0;" x1="725.5" x2="1549.5" y1="332.625" y2="332.625"/><text fill="#000000" font-family="sans-serif" font-size="13" lengthAdjust="spacing" textLength="120" x="737.5" y="327.5591">[7] Security Report</text><polygon fill="#181818" points="967.5,357.7578,977.5,361.7578,967.5,365.7578,971.5,361.7578" style="stroke:#181818;stroke-width:1.0;"/><line style="stroke:#181818;stroke-width:1.0;" x1="720.5" x2="973.5" y1="361.7578" y2="361.7578"/><text fill="#000000" font-family="sans-serif" font-size="13" lengthAdjust="spacing" textLength="235" x="727.5" y="356.6919">[8] Deploy Chain to Managed Cluster</text><polygon fill="#181818" points="1179.5,386.8906,1189.5,390.8906,1179.5,394.8906,1183.5,390.8906" style="stroke:#181818;stroke-width:1.0;"/><line style="stroke:#181818;stroke-width:1.0;" x1="979.5" x2="1185.5" y1="390.8906" y2="390.8906"/><text fill="#000000" font-family="sans-serif" font-size="13" lengthAdjust="spacing" textLength="188" x="986.5" y="385.8247">[9] Setup Blockchain Explorer</text><polygon fill="#181818" points="1298,416.0234,1308,420.0234,1298,424.0234,1302,420.0234" style="stroke:#181818;stroke-width:1.0;"/><line style="stroke:#181818;stroke-width:1.0;" x1="979.5" x2="1304" y1="420.0234" y2="420.0234"/><text fill="#000000" font-family="sans-serif" font-size="13" lengthAdjust="spacing" textLength="143" x="986.5" y="414.9575">[10] Expose Endpoints</text><polygon fill="#181818" points="234.5,460.2891,244.5,464.2891,234.5,468.2891,238.5,464.2891" style="stroke:#181818;stroke-width:1.0;"/><line style="stroke:#181818;stroke-width:1.0;" x1="43.5" x2="240.5" y1="464.2891" y2="464.2891"/><text fill="#000000" font-family="sans-serif" font-size="13" lengthAdjust="spacing" textLength="179" x="50.5" y="444.0903">[11] Review &amp; Update Chain</text><text fill="#000000" font-family="sans-serif" font-size="13" lengthAdjust="spacing" textLength="74" x="50.5" y="459.2231">(if required)</text><polygon fill="#181818" points="442.5,489.4219,452.5,493.4219,442.5,497.4219,446.5,493.4219" style="stroke:#181818;stroke-width:1.0;"/><line style="stroke:#181818;stroke-width:1.0;" x1="246.5" x2="448.5" y1="493.4219" y2="493.4219"/><text fill="#000000" font-family="sans-serif" font-size="13" lengthAdjust="spacing" textLength="184" x="253.5" y="488.356">[12] Push Updates to GitHub</text><polygon fill="#181818" points="708.5,518.5547,718.5,522.5547,708.5,526.5547,712.5,522.5547" style="stroke:#181818;stroke-width:1.0;"/><line style="stroke:#181818;stroke-width:1.0;" x1="454.5" x2="714.5" y1="522.5547" y2="522.5547"/><text fill="#000000" font-family="sans-serif" font-size="13" lengthAdjust="spacing" textLength="242" x="461.5" y="517.4888">[13] Trigger Automated CI/CD Pipeline</text><polygon fill="#181818" points="1827,547.6875,1837,551.6875,1827,555.6875,1831,551.6875" style="stroke:#181818;stroke-width:1.0;"/><line style="stroke:#181818;stroke-width:1.0;" x1="720.5" x2="1833" y1="551.6875" y2="551.6875"/><text fill="#000000" font-family="sans-serif" font-size="13" lengthAdjust="spacing" textLength="278" x="727.5" y="546.6216">[14] Deploy Updates to Testnet (Validation)</text><polygon fill="#181818" points="731.5,576.8203,721.5,580.8203,731.5,584.8203,727.5,580.8203" style="stroke:#181818;stroke-width:1.0;"/><line style="stroke:#181818;stroke-width:1.0;" x1="725.5" x2="1838" y1="580.8203" y2="580.8203"/><text fill="#000000" font-family="sans-serif" font-size="13" lengthAdjust="spacing" textLength="143" x="737.5" y="575.7544">[15] Validation Results</text><polygon fill="#181818" points="967.5,621.0859,977.5,625.0859,967.5,629.0859,971.5,625.0859" style="stroke:#181818;stroke-width:1.0;"/><line style="stroke:#181818;stroke-width:1.0;" x1="720.5" x2="973.5" y1="625.0859" y2="625.0859"/><text fill="#000000" font-family="sans-serif" font-size="13" lengthAdjust="spacing" textLength="163" x="727.5" y="604.8872">[16] Deploy to Production</text><text fill="#000000" font-family="sans-serif" font-size="13" lengthAdjust="spacing" textLength="106" x="727.5" y="620.02">(Post-Validation)</text><polygon fill="#181818" points="1406.5,665.3516,1416.5,669.3516,1406.5,673.3516,1410.5,669.3516" style="stroke:#181818;stroke-width:1.0;"/><line style="stroke:#181818;stroke-width:1.0;" x1="979.5" x2="1412.5" y1="669.3516" y2="669.3516"/><text fill="#000000" font-family="sans-serif" font-size="13" lengthAdjust="spacing" textLength="220" x="986.5" y="649.1528">[17] Enable Continuous Monitoring</text><text fill="#000000" font-family="sans-serif" font-size="13" lengthAdjust="spacing" textLength="96" x="986.5" y="664.2856">&amp; Optimization</text><polygon fill="#181818" points="54.5,694.4844,44.5,698.4844,54.5,702.4844,50.5,698.4844" style="stroke:#181818;stroke-width:1.0;"/><line style="stroke:#181818;stroke-width:1.0;" x1="48.5" x2="1417.5" y1="698.4844" y2="698.4844"/><text fill="#000000" font-family="sans-serif" font-size="13" lengthAdjust="spacing" textLength="251" x="60.5" y="693.4185">[18] Performance and Health Feedback</text><!--SRC=[ZLHDSzCm4BtxL-pqq4aF7GYqfN1W1fpGvi3WIKClnEDHx4sYYICPVPI6NuyaMxBZ6EZDNkrxkzfzJoHNNC04dx3a5Oe8cQBg036NUnuBibO-SaVLlLxvlxDuzYgUG48hB2d3Co0IubaMJp8V2fbV2ICRB20kjLGeN6eJovfOoFrSydoNRmbbC7skIYwQ_3QU-RZ7J5bHSSgKR0joHisbADl0WlDIrXL3C7F1aFs0kHRswm754ysnJlVHp4VRYtEsfXijYAASmICAkgQv-wc7u8wpRjn35oWLGnL5OTfm-R4pQVW0FyOfp4oZb2Y4sCqX5kXObinNHaY887iqWvDH1-x8JgfRrZSfF9AI5ewrsx_5do9EkdgRmXV4OaNo7PZpOueb6z4r47O0AgL6UT7hgHQEfRbAuGuPYd2v9Kkqt1g-0bT48YZkPTQ0R2T7gh8qrwbPZz8L76imwcKQxCaMBVmcXGJ5cejzE3VTOBwJqMd-O0FlqXOvnueBDL2x9t6BkqsDqOnw3yrgpNLxveZwA4Cqe7rBzjvFOS0pGpJ19qvchrERpCtCM__yIvP6btDyelWBpk5xLNGsQ9SlyAUc0ek_htvi9EXsNOFb2rSzDifR2BhPcAO-QSNt1blyV- -Dqnp3LHXwfxHF63MsC3g-Y7nmk9Fhu25haJbANPgPlMZluvlGWwcT25xelBRqAE5INNQR6DXS_-bob4Q3KqPMfJEqeanptNtabkmSlbMAxkdl-Wqw8J74xS8justm1M4v6aCNS8-aLDlW_UWF]--></g></svg>GAKTmh7YOpJQy_E41HsTSLiSEYfKeHXs7Itx4kN9Jasdt-u9r0n32jDlLGbHMZixUSKGYRSb6SGSMkfmBoIFTLDpYBnblbVYajYwgQBS41UMMIt5rJAFaAw3OzaKXXklps7O_f_TsL7V-EIIl5gzgWeANMQ3ifhKPGhJvMrE2zpRsqtNqjK1DqW1LEm93Mu03W6YlzA-FeRS1Xn7-OJ.svg…]()


