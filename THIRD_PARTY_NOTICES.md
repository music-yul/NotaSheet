# NotaSheet — 오픈소스 라이선스 및 저작권 고지

NotaSheet는 음악 활동지 제작을 위한 웹 애플리케이션입니다. 아래 외부 오픈소스는 각 원저작자의 저작물이며, NotaSheet 자체의 라이선스와 별도로 적용됩니다.

## 사용 중인 외부 라이브러리

- **Tiptap 3.31.3**: `@tiptap/core`, `@tiptap/starter-kit`, `@tiptap/extension-table`, `@tiptap/extension-table-row`, `@tiptap/extension-table-cell`, `@tiptap/extension-table-header`, `@tiptap/extension-underline`, `@tiptap/extension-text-align`. MIT License. https://github.com/ueberdosis/tiptap
- **VexFlow 4.2.6**: 악보 렌더링 엔진. MIT License. https://github.com/vexflow/vexflow

두 라이브러리는 jsDelivr CDN에서 불러옵니다. Tiptap은 ProseMirror 등 하위 의존성을 사용할 수 있으며, CDN이 불러오는 모든 하위 패키지의 라이선스와 고지는 배포 전 별도 확인이 필요합니다. Tiptap 유료 기능 및 Cloud 서비스는 이 버전에 통합하지 않았습니다.

Bravura 등의 폰트 파일은 현재 NotaSheet 저장소에 별도로 번들하지 않습니다. 추후 폰트를 번들하는 경우 해당 폰트의 저작권 및 OFL 전문을 추가해야 합니다.

## Tiptap — MIT License

MIT License

Copyright (c) 2025, Tiptap GmbH

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## VexFlow — MIT License

MIT License

Copyright (c) 2023-present VexFlow contributors (see AUTHORS.md).
Copyright (c) 2010-2022 Mohit Muthanna Cheppudira

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

## 참고

- Tiptap 라이선스 원문: https://github.com/ueberdosis/tiptap/blob/main/LICENSE.md
- VexFlow 라이선스 원문: https://github.com/vexflow/vexflow/blob/main/LICENSE
- 이 문서는 확인한 직접 의존성의 고지를 담습니다. 하위 의존성의 포괄적인 법적 검토를 완료했다는 뜻은 아닙니다.
