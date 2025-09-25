# 🥬 농산물 커머스 RAG 기반 사내 챗봇 ― **채채봇**
사내 채소 정보를 조회할 수 있는 LLM 기반 챗봇 시스템.

---

## 📌 프로젝트 개요

- **프로젝트명**: 채채봇 (ChaeChae Bot)
- **한줄 소개**: 농산물 커머스용 **사내 지식 기반 챗봇**(RAG)
- **개발 기간**: 2025-08-01 ~ 2025-09-25
- **배포 링크**: _(추가 예정)_

---

## ✨ 핵심 기능

- **문서 인덱싱 자동화**: S3 업로드 → PDF 로드 → 청킹 → **ChromaDB** 벡터화 → 검색
- **RAG 챗봇**: 매뉴얼 출처를 근거로 답변을 제시
- **관측/모니터링**: Prometheus + Grafana  )

  ---
# 🥝 Wiki
<ul>
  <li><a href="https://github.com/team-chaechae/.github/wiki/Branch-%EC%9E%91%EC%84%B1-%EA%B0%80%EC%9D%B4%EB%93%9C%EB%9D%BC%EC%9D%B8">Branch 작성 가이드라인</a></li>
  <li><a href="https://github.com/team-chaechae/.github/wiki/Pull-Request-%EA%B0%80%EC%9D%B4%EB%93%9C%EB%9D%BC%EC%9D%B8">Pull Request 작성 가이드라인</a></li>
    <li><a href="https://github.com/team-chaechae/.github/wiki/Commit-%EC%9E%91%EC%84%B1-%EA%B0%80%EC%9D%B4%EB%93%9C">Commit 작성 가이드라인</a></li>
  <li><a href="https://github.com/team-chaechae/.github/wiki/Code-%EC%BB%A8%EB%B0%B4%EC%85%98-%EA%B0%80%EC%9D%B4%EB%93%9C%EB%9D%BC%EC%9D%B8">Code 컨밴션 가이드라인</a></li>
  <li><a href="https://github.com/team-chaechae/.github/wiki/DTO-%EC%BB%A8%EB%B0%B4%EC%85%98-%EA%B0%80%EC%9D%B4%EB%93%9C%EB%9D%BC%EC%9D%B8">DTO 컨밴션 가이드라인</a></li>
  <li><a href="https://github.com/team-chaechae/.github/wiki/Package-%EC%BB%A8%EB%B0%B4%EC%85%98">Package 컨밴션 가이드라인</a></li>
</ul>

---

# 🤖 ERD 다이어그램
![채채erd](https://github.com/user-attachments/assets/6fdc6dfb-d4ad-4549-afaa-b4e32fc8ded0)

---

## ✨ 트러블슈팅

  <ul>
    <li><a href="https://github.com/team-chaechae/.github/wiki/%EA%B2%80%EC%83%89%EA%B8%B0-%EC%84%B1%EB%8A%A5-%EA%B0%9C%EC%84%A0">검색기 성능 개선</a></li>
    <li><a href="https://github.com/team-chaechae/.github/wiki/Spring-%E2%86%92-FastAPI-%ED%86%B5%EC%8B%A0%EC%97%90%EC%84%9C-422-Invalid-HTTP-request-%EC%9B%90%EC%9D%B8%EA%B3%BC-%ED%95%B4%EA%B2%B0">Spring → FastAPI 통신에서 422 Invalid HTTP request 원인과 해결</a></li>
  </ul>
