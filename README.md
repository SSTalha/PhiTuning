# FineTuning Microsoft Phi 1_5 on Custom Fashion Dataset
-----------------------------------------------------------------------

## Requirements
```python
!pip install bitsandbytes==0.40.0.post4
!pip install -qqq torch==2.1.0
!pip install -qqq -U transformers==4.30.0
!pip install -qqq -U peft==0.6.0
!pip install -qqq -U accelerate==0.24.1
!pip install -qqq datasets==2.14.6
!pip install -qqq loralib==0.1.1
!pip install -qqq einops==0.6.1
```
```python
HuggingFacce_Token = your_huggingface_api_token
```
----------------------------------------------------------------------------
### Techniques Used

To compensate for using only 1 T4 GPU. I used:
1- PEFT
2- LoRA
3- Quantization
