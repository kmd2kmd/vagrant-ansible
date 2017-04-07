## GitLab 構築注意点
- `vagrant up` 後、ウェブブラウザからアクセスしても GitLab が表示されない。`vagrant reload` を行って VM を再起動後にウェブブラウザからアクセスできるようになる。
- VM の割当メモリが 512 MB の場合、`gitlab-ctl reconfigure` の時間が多くかかるのと、ウェブブラウザからのレスポンスが非常に遅いため、1 GB 割り当てている。