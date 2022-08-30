### Stable DiffusionをGoogle Colab上で実行する手順

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
セルを実行してします。  
https://github.com/Hideki-Kagaya/Stable_Diffusion_Simply/blob/main/stable_diffusion.ipynb  
5. 約3～4分ほど待って1番目のセルの実行が完了したら、2番目のセルの右側に何か好きな英文を入れて  
セルを実行します。そのまま1分ほど待つと、入力した英文に基づいて画像が自動生成されます。

※Google Golabページを開いたら、まずは画面左上の「編集」-「ノートブックの生成」より、  
「ハードウェア アクセラレータ」の項目が「GPU」になっていることをご確認ください。  
※Google Chromeをご使用の場合は、3番目のセルを実行すると生成された画像が  
PNGファイルとしてダウンロードされます。  
※一度4の手順を実行した後は、再度Google Colabページを開き直す、またはしばらく操作をしないなどして  
セッションが切断されるまでは、再度同じ手順を実施することなく2番目のセルから画像の再生成が可能です。

なお、ノートブックの作成にあたっては、主に下記Webサイトを参考にさせていただきました。  
http://cedro3.com/ai/stable-diffusion/  
https://self-development.info/%E3%80%90%E7%B0%A1%E5%8D%98%E3%80%91%E3%83%AD%E3%83%BC%E3%82%AB%E3%83%AB%E7%92%B0%E5%A2%83%E3%81%A7stable-diffusion%E3%81%A7%E5%AE%9F%E8%A1%8C%E3%81%99%E3%82%8B%E6%96%B9%E6%B3%95/  

ちなみに、 **「Evil Dxxxxxxn」** と入力して生成された画像がこちら。  
※伏字の部分はご想像におまかせします  
![Evil Doraemon](https://raw.githubusercontent.com/Hideki-Kagaya/Stable_Diffusion_Simply/main/evil_d______n.png)
