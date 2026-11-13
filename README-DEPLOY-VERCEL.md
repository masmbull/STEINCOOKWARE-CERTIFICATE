# STEINCOOKWARE Official Documents

Static website containing:
- GREBLON Certificate
- SGS Test Report

## Deploy with Vercel CLI

1. Extract this ZIP.
2. Open PowerShell in the extracted `steincookware-documents` folder.
3. Run:

   ```powershell
   npx vercel
   ```

4. Follow the prompts:
   - Set up and deploy: Yes
   - Select your Vercel account/team
   - Link to existing project: No (first deployment)
   - Project name: `steincookware-documents`
   - Directory: `./`
   - Override settings: No

5. For production deployment, run:

   ```powershell
   npx vercel --prod
   ```

The site is static; no build command or environment variables are required.

## Deploy through GitHub

Push this folder to a GitHub repository, then in Vercel choose
Add New → Project → Import the repository. Keep the framework preset as
Other, leave Build Command empty, and set Output Directory to `.`.
Deploy.

After deployment, test both documents on a phone. The old Cloudflare URL
and QR code do not automatically redirect to the new Vercel URL.
Generate a new QR code after the final Vercel URL is confirmed.
