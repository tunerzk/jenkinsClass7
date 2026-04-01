Deliverables:

Students will spin up S3 in terraform with uploaded pictures and screenshots
<img width="1453" height="147" alt="image" src="https://github.com/user-attachments/assets/0bf16f00-da04-46d6-ac97-9bce4b08f0f2" />

ARMAGEDDON REPO LINK:
https://github.com/tunerzk/Armageddongroupwork

SUCCESSFULL WEBHOOK INVOCATION FROM STUDENTS OWN GITHUB:
<img width="1846" height="583" alt="image" src="https://github.com/user-attachments/assets/4911a073-de9e-42af-ac9e-1b9aa8510900" />
<img width="1340" height="470" alt="image" src="https://github.com/user-attachments/assets/e0ec4b34-0786-4f12-bd60-5f3875eaf784" />


<img width="1586" height="381" alt="image" src="https://github.com/user-attachments/assets/d08389f5-5f13-4bca-b305-925bbc576699" />
<img width="712" height="267" alt="image" src="https://github.com/user-attachments/assets/47e8d8cd-2a04-4503-b944-006378b4c151" />
<img width="1304" height="634" alt="image" src="https://github.com/user-attachments/assets/f5739d3e-514a-4884-9c2c-990c1856192a" />
<img width="1546" height="904" alt="image" src="https://github.com/user-attachments/assets/bece07da-e8e6-4bdf-8345-3c50c2b98b7a" />
<img width="1372" height="817" alt="image" src="https://github.com/user-attachments/assets/4127acc4-f01d-4fa7-a2ba-fd917c50685a" />

PROOF OF UPDATE VERSIONS OF PYTHON and JAVA:
<img width="730" height="213" alt="image" src="https://github.com/user-attachments/assets/053014ee-e309-49da-a245-6e8c3caf5cc8" />


TERRAFORM S3 BUCKET CODE:
<img width="774" height="364" alt="image" src="https://github.com/user-attachments/assets/f37f969e-477a-4cff-8b89-1903e8f86bfd" />

terraform {
  backend "s3" {
    bucket         = "terraform-state-kevjenkinstest"
    key            = "jenkins/terraform.tfstate"
    region         = "us-east-1"
    dynamodb_table = "terraform-locks"
    encrypt        = true
    use_lockfile   = true
  }
}
######################################################################











