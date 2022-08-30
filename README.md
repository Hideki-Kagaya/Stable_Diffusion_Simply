#### Stable DiffusionをGoogle Colab上で実行する手順

1. Hugging Faceトップページ右上の「Sing Up」よりアカウントを作成します。  
https://huggingface.co/
2. Hugging Faceの「Stable Diffusion」プロジェクトページに移動してライセンスを確認し、  
「I have read the Licence and agree with its terms」にチェックを入れて  
「Access repository」をクリックします。  
https://huggingface.co/CompVis/stable-diffusion-v1-4
3. 下記ページの「New Token」をクリックして任意の名前を入力し、  
「Generate a token」をクリックするとトークンが表示されます。
https://huggingface.co/settings/tokens
4. 下記ページの「Open in Colab」ボタンをクリックするとGoogle Colabページに遷移します。
1番目のセルの右側のテキストボックスに手順3で表示されたトークンをコピー＆ペーストし、
セルを実行してください。
https://github.com/Hideki-Kagaya/Stable_Diffusion_Simply/blob/main/stable_diffusion.ipynb
5. 約3～4分ほど待って1番目のセルの実行が完了したら、2番目のセルの右側に何か好きな英文を入れて  
セルを実行します。そのまま1分ほど待つと、入力した英文に基づいて画像が自動生成されます。

※Google Chromeをご使用の場合は、3番目のセルを実行すると生成された画像が  
PNGファイルとしてダウンロードされます。
※一度4の手順を実行した後は、再度Google Colabページを開き直す、またはしばらく操作をしないなどして  
セッションが切断されるまでは、再度同じ手順を実施することなく2番目のセルから画像の再生成が可能です。
