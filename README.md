# paper2

* BERT, FINBERT 이용 아래 데이터셋 분류 테스트

- dataset = load_dataset('financial_phrasebank', 'sentences_75agree')
- #data = pd.read_csv('/content/drive/MyDrive/paper/FiQA_Financial PhraseBank.csv')
- #data = pd.read_csv('/content/drive/MyDrive/paper/SEntFiN-v1.1_filtered.csv')
- data = pd.read_csv('/content/drive/MyDrive/paper/financial_phrasebank_auditor_sentiment.csv')

* confusion_matrix 출력

* 파일 생성 및 저장
- pd.to_csv('/content/drive/MyDrive/paper/financial_phrasebank_auditor_sentiment.csv')
