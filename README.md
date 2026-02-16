# KYROS Marketing Command Center

Interactive dashboard for the KYROS marketing team.

## Features

- **Overview**: Key metrics, sales funnel visualization, strategy summary
- **Channels**: FB/IG, YouTube, Google, Influencer/Podcast with budgets and tactics
- **90-Day Plan**: Interactive task checklist with persistence (saves to localStorage)
- **Sales Playbook**: Discovery call scripts, SDR qualification, objection handling
- **Ad Creatives**: Library with image upload capability, add/delete creatives
- **Budget**: Monthly allocation breakdown with visual bars
- **Metrics**: KPIs by funnel stage, success milestones

## Deploy to Vercel

### Option 1: Drag & Drop (Easiest)

1. Go to [vercel.com](https://vercel.com)
2. Sign in with GitHub, GitLab, or email
3. Click "Add New" → "Project"
4. Drag this entire folder into the upload area
5. Click Deploy
6. Your dashboard will be live at `your-project.vercel.app`

### Option 2: Vercel CLI

```bash
npm i -g vercel
cd kyros-marketing-dashboard
vercel
```

### Option 3: GitHub Integration

1. Push this folder to a GitHub repo
2. Connect repo to Vercel
3. Auto-deploys on every push

## Custom Domain

After deployment:
1. Go to Project Settings → Domains
2. Add `marketing.kyrosconsulting.com` (or your preferred subdomain)
3. Add the DNS records Vercel provides to your domain registrar

## Data Persistence

- Task completions and custom ad creatives are saved to `localStorage`
- Data persists per browser/device
- For team-wide persistence, you'd need to add a backend (Firebase, Supabase, etc.)

## Customization

All content is in `index.html`. Edit directly to update:
- Metrics and targets
- Channel budgets
- Sales scripts
- Default ad creatives
- Timeline tasks

---

Built for KYROS Consulting | 2026
