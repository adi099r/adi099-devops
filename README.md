## DevOps Project 01

This project demonstrates a simple DevOps workflow using Terraform and Docker.

### Project Structure

```
app.py
Dockerfile
terraform-configs/
	backend.tf
	main.tf
	provider.tf
	terraform.tfstate
	terraform.tfstate.backup
	variables.tf
```

### What has been covered so far

- **Terraform Configuration**: Basic setup with `main.tf`, `provider.tf`, and `variables.tf`.
- **State Management**: Includes `terraform.tfstate` and backup.
- **Backend Configuration**: `backend.tf` for remote state (if configured).
- **Docker Integration**: `Dockerfile` present for containerizing the application.
- **Python Application**: `app.py` as the main application file.

---
*Update this README as you add more features or infrastructure.*
