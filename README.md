# ConclaveRepo
Conclaveを学習するためのリポジトリです。

## Why Conclave
データ所有者は、情報を第三者と共有すると、その情報に対する絶対的な支配力を失います。Conclaveは、ユーザーがプライバシーを重視したアプリケーションを大規模に構築、展開、統合できるようにすることで、データ所有者がコントロールを取り戻せるよう支援します。

Conclaveを使用すると、次のようなものを構築できます。

- 使用中のデータを保護するアプリケーション
- 誰もデータを改ざんしていないことを示すデジタル証拠を提供するアプリケーション。
- 複数当事者による安全なデータ共有のためのソリューション

## What is Conclave

Conclaveは、エンクレーブと呼ばれるハードウェアベースのTrusted Execution Environments（TEE）を使用して、プライバシーを重視したアプリケーションを迅速に開発するためのソフトウェア開発キットです。Conclaveは、Intel® Security Guard Extension (SGX) を使用したコンフィデンシャル・コンピューティングを開発者がより利用しやすいものにします。

## コンパイル方法

```bash
cd conclave-tutorials/hello-world
./gradlew :host:bootJar :client:shadowJar --stacktrace --debug
```

### 参考文献
1. [Introduction to Conclave](https://docs.conclave.net/)
2. [R3Conclave/conclave-core-sdk](https://github.com/R3Conclave/conclave-core-sdk)
3. []()
4. []()