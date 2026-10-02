# pimp dorker

automating google dork searches because manually copying fifty queries into a browser and solving captchas will drive anyone insane

built this for security assessments to quickly pull exposed directories backup files and vulnerable endpoints

## what it does

takes your custom dork list or single query
extracts root domains and clean urls
saves everything organized in text files for piping into your recon tools
handles rate limits and errors without crashing

## install and run

```bash
git clone https://github.com/igotlinux/pimp-dorker.git
cd pimp-dorker
pip3 install -r requirements.txt
python3 pimpdorker.py
```

enter your target dork query set the result count and let it dump the urls

## heads up

intended strictly for authorized security assessments bug bounty hunting on scoped domains and educational research do not test things you do not own

## license

mit
