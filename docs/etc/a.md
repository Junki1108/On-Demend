# Information Protection
### Not Resolved

```bash
#include <stdio.h>
int main() {
        printf("\n=====================================\nSeoHeewon Talmo Program\n=====================================\n\n");
        char ddd[100];
        int a;
        printf("\n[System] 숫자를 입력하세요.\n>> ");
        scanf("%d", &a);
        getchar();
        printf("\n[System] 문자를 입력하세요.\n>> ");
        fgets(ddd, sizeof(ddd), stdin);
        for (int i = 0; i <= sizeof(ddd) ; i++) {
                if (ddd[i] >= 'A' && ddd[i] <= 'Z') {
                        if (ddd[i] + a >= 'Z') {
                                ddd[i] = ddd[i] - 26;
                        }
                        ddd[i] = ddd[i] + a;
                } if (ddd[i] >= 'a' && ddd[i] <= 'z') {
                        if (ddd[i] + a >= 'z') {
                                ddd[i] = ddd[i] - 26;
                        }
                        ddd[i] = ddd[i] + a;
                }
        }
        printf("%s", ddd);
        return 0;
}
```