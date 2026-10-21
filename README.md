# red-edits

Claude가 작성·수정·채워 넣은 부분을 **빨간 글자**로 표시하는 Claude 스킬입니다.
예시: [`examples/전기사용신청서.html`](examples/전기사용신청서.html)

## 설치 방법

### 1) Claude Code 플러그인
```
/plugin marketplace add dudu1258/red-edits
/plugin install red-edits@dudu1258-skills
```

### 2) skills.sh (npx skills)
```
npx skills add dudu1258/red-edits
```

### 3) .skill 파일 (Claude.ai / 데스크톱 앱)
[Releases](https://github.com/dudu1258/red-edits/releases)에서 `red-edits.skill`을 내려받아
설정 → Capabilities → Skills → 업로드. (리포의 `dist/red-edits.skill`도 동일)

수동 설치: 압축을 풀어 `~/.claude/skills/red-edits/SKILL.md`에 두면 됩니다.

## 사용
"수정한 부분 빨간색으로", "변경 표시해줘" 또는 `/red-edits`
