# FPGA Architecture Interactive Diagram

An interactive educational diagram showing the essential components of FPGA (Field-Programmable Gate Array) architecture for digital logic students.

![FPGA Diagram Preview](preview.png)

## Features

- **Interactive exploration** — Click on components or quick-reference cards to learn details
- **Six core components covered:**
  - Configurable Logic Blocks (CLBs)
  - Programmable Interconnect
  - I/O Blocks (IOBs)
  - Block RAM (BRAM)
  - Clock Distribution Network
  - Configuration Memory (SRAM)
- **No dependencies** — Pure HTML/CSS/JavaScript, works in any modern browser
- **Mobile responsive** — Works on tablets and phones

## Quick Start

1. Open `index.html` in any web browser
2. Click on components in the diagram or use the quick-reference cards at the bottom

## Hosting on GitHub Pages

1. **Fork or clone this repository**

2. **Enable GitHub Pages:**
   - Go to your repository on GitHub
   - Click **Settings** → **Pages** (in the left sidebar)
   - Under "Source", select **main** branch
   - Click **Save**

3. **Access your site:**
   - Your diagram will be live at: `https://YOUR-USERNAME.github.io/REPO-NAME/`
   - It may take 1-2 minutes to deploy

## Embedding in zyBooks

Once hosted, provide your zyBooks representative with the GitHub Pages URL to embed as custom web content.

Alternatively:
- Take a screenshot for static use
- Link to the hosted version for full interactivity

## Customization

The diagram is a single HTML file with embedded CSS and JavaScript. To customize:

- **Colors:** Edit the CSS variables and color values (search for hex codes like `#3b82f6`)
- **Content:** Edit the `componentInfo` object in the `<script>` section to change descriptions
- **Layout:** Modify the SVG coordinates to rearrange components

## License

Free to use for educational purposes. Attribution appreciated but not required.

## Credits

Created for digital logic education. Components based on standard FPGA architecture (similar to Xilinx/AMD and Intel/Altera devices).
