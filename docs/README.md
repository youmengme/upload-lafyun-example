# Hello 

```yml
- name: deploy
    id: hello
    uses: youmengme/upload-lafyun@v1.0
    env:
        USER_ACCOUNT: ${{ secrets.LAF_ACCOUNT }}
        PASSWORD: ${{ secrets.LAF_PASSWORD }}
        APPID: ${{ secrets.LAF_APPID }}
        REGION: ${{ secrets.LAF_REGION }}
        BUCKET: ${{ secrets.LAF_BUCKET }}
        ASSET_PATH: './dist'
```
