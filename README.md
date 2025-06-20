# Midstay Cursor Rules

This repo contains shared [Cursor](https://cursor.so) rules for Ruby on Rails projects. It includes prompts and conventions for testing, architecture, and AI-assisted workflows.

## Add as a Submodule

From your project root:

```bash
git submodule add https://github.com/midstay/cursor-rules .cursor/rules
```

## Update the Submodule

To pull the latest changes:

```bash
cd .cursor/rules
git pull origin main
cd ../..
git add .cursor/rules
git commit -m "Update cursor rules submodule"
git push
```

Or use the shortcut:

```bash
git submodule update --remote --merge
```

Then commit the updated pointer as above.

## License

MIT – see [LICENSE](LICENSE).
