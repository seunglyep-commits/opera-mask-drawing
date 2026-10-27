# 프로젝트 지침 (Project Guidelines)

## 프로젝트 식별 정보
- **앱 이름**: 경극/변검 분장 디지털 드로잉 (`opera-mask-drawing`)
- **GitHub 저장소 URL**: `https://github.com/seunglyep-commits/opera-mask-drawing`
- **Vercel projectId**: `prj_U1lIuQivtxMWOPztGSYr8Ob0kkXQ`
- **Vercel orgId**: `team_VUFrOfhjrj52Y8NK9isbNQvB`
- **Vercel projectName**: `opera-mask-drawing`
- **Supabase project ref**: 해당 없음 (클라이언트 단일 페이지 캔버스 드로잉 앱으로 서버 DB 저장 불필요)

## 보안 및 배포 원칙
- `.env.local`, 인증 파일, `.vercel`, 비밀값, 학생 개인정보를 Git에 커밋하지 않는다.
- 배포 전 `.vercel/project.json`의 `projectId` 및 `orgId`를 대조한다.
