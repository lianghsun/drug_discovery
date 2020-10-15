# 西藥房 x TW AI Hackathon
目前全球新藥開發領域正運用AI技術進行候選藥物篩選及結構設計，利用數據驅動（Data-Driven）的思維引導與輔助頂尖藥物設計科學家之藥物開發工作，將是前瞻性藥物開發新技術之重大突破與轉折契機。藥物發展極為複雜且極為耗時，包含：（1）標的選擇與確認（2）化合物篩選與主要結構優化（3）臨床前試驗（4）臨床試驗。傳統藥物發展程序為：當化學結構之作用確認後，輔以藥物專家或化學家定義的Rule-Based規則（in silico、QSAR、logP等）與細胞功能測試成為候選藥物，接續進行動物體內試驗與臨床試驗，用以驗證分子功效與生物毒性作用。但並非所有的藥物都吻合Rule-Based，且美國發展一種新藥平均需耗費26億美金與歷時12年。如何減少研發成本與縮短藥物開發時程，為產業最大挑戰與最緊急之問題，我們希望能透過 AI 模型去學習如何探索新藥開發

## Prerequisites
- Install RDKit from https://www.rdkit.org/

## Dataset
- Download SMILES from https://zinc.docking.org/tranches/home/

## Run Main
We have prepared token file for this project, so please skip `Load Training Data` section and run all of rest code.
Due to VAE, sometimes it might not generate new compound (sampling problem), please run more times to get valid compound.

## Oh, you have own dataset?
1. Please create a folder named `dataset`, and place your `.smi` files in this folder.
2. run `preprocess` to create new token file for your dataset, then run `main` to train your model

## last..
Enjoy your new compound!
