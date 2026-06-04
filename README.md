# 준영의 Life Command System

Netlify에서 GitHub Pages로 이전한 사이트입니다.

🌐 **Live URL**: https://hamster9212.github.io/junyeong-life-system-pages/

## Cloudflare Pages 자동 배포 설정

`main` 브랜치에 push하면 GitHub Actions가 자동으로 Cloudflare Pages에 배포합니다.

### 필요한 GitHub Secrets 설정:
- `CLOUDFLARE_API_TOKEN` — Cloudflare API 토큰
- `CLOUDFLARE_ACCOUNT_ID` — Cloudflare 계정 ID  
- `CLOUDFLARE_ZONE_ID` — Cloudflare Zone ID (선택사항, 캐시 자동 purge용)

> Cloudflare Dashboard → 이메일 인증 후 Pages 프로젝트 연결 필요
