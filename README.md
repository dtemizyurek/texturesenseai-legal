# TextureSenseAI Legal Documents

This directory contains the legal documents for TextureSenseAI.

## Files

- **privacy-policy.html** - Privacy Policy
- **terms-of-service.html** - Terms of Service  
- **index.html** - Landing page with links to both documents

## Hosting on GitHub Pages

### Setup Steps:

1. **Commit these files to your repository**:
```bash
git add docs/
git commit -m "Add Privacy Policy and Terms of Service"
git push
```

2. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Settings → Pages
   - Source: Deploy from a branch
   - Branch: `main` (or `master`)
   - Folder: `/docs`
   - Save

3. **Your URLs will be**:
```
https://[your-username].github.io/TextureSenseAI/
https://[your-username].github.io/TextureSenseAI/privacy-policy.html
https://[your-username].github.io/TextureSenseAI/terms-of-service.html
```

## Next Steps

1. **Update Info.plist** with your GitHub Pages URLs
2. **Update PremiumPaywallViewController** with the URLs
3. **Test the links** in your app
4. **Submit to App Store**

## Customization

Before deploying, update these placeholders:

- [ ] Email addresses (support@, privacy@)
- [ ] Jurisdiction in Terms of Service (Section 13)
- [ ] Company name (if applicable)
- [ ] Pricing (currently $9.99/month)

## Contact

For questions about these documents:
- Email: support@texturesenseai.com
- Privacy: privacy@texturesenseai.com
