cloudformation_study
====

## What is this?

エンジニアリングスクール[RaiseTech](https://raise-tech.net/)のAWSフルコース第8回講座の課題：「過去にWEBGUIで構築したリソース（EC2,RDS,S3,ALB）をテンプレートで再現」を実施したものです。
- 本課題に関して詳細な手順書等のドキュメントはスクールより提供されておらず、AWS公式ドキュメントや検索サイトで入手可能な情報を元に作成しています。
- テンプレートはYAMLで作成しています。また、構築時に記入したコメント行は削除しています。


## 構成

- 東京リージョンで単一VPCを作成して実施
- 詳細はlayout/layout.pngをご覧ください。

## 作成環境

- Amzxon Linux 2 (ami-0c3fd0f5d33134a76)
- RDS (エンジンバージョン MySQL 5.7.22)

## 導入

- AWSのCloudFormationから読込が可能です。
- EC2からS3に対してはs3fsにてRollを使用した方法でマウントしてください。

## 参考サイト

- [AWS CloudFormation ユーザーズガイド テンプレートリファレンス](https://docs.aws.amazon.com/ja_jp/AWSCloudFormation/latest/UserGuide/template-reference.html)
- [【Tips】CloudFormationでDependOnが必要なケース](https://dev.classmethod.jp/cloud/aws/cfn-dependon/)

## 作成者

[@miima_17](https://twitter.com/miima_17)
