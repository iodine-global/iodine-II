# Iodine II 

**Iodine II is the 2nd version of the unblockable unblocked games site, Iodine.** It achieves its stealth status by using a Google Doc as its homepage and loading the actual site via a jsDelivr-hosted HTML structure.

Most network filters automatically block standard gaming domains, but they rarely block Google Docs or jsDelivr due to their widespread use in schools and workplaces. This project exploits that blind spot to keep games accessible.

## How It Works

* **The Homepage:** A public **Google Doc** acts as the front door, housing the setup instructions and dynamic links.
* **The Engine:** The actual gaming interface is a single **HTML** file.
* **The Delivery:** The site assets and scripts are hosted and delivered through **jsDelivr**, a trusted open-source CDN.

## Repository Structure

* `Iodine.2.r1.laptop/` — Contains the core source files, assets, and configuration for Iodine 2.0.
* `LICENSE` — Project terms under the **GPL-3.0 License**.
* `README.md` — Project documentation.

## Setup & Deployment

1. **Upload to GitHub:** Fork this repository and push your game assets to your main branch.
2. **Get jsDelivr Link:** Copy your raw HTML entry point link from the `Iodine.2.r1.laptop` directory and format it using jsDelivr: `https://jsdelivr.net`.
3. **Configure Google Doc:** Create a public Google Doc, paste the jsDelivr link inside, and share the Doc URL with your users.

## License

This project is licensed under the **GNU General Public License v3.0 (GPL-3.0)** - see the [LICENSE](LICENSE) file for details.
