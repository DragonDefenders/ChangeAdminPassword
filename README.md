# ChangeAdminPassword
Set-ADAccountPassword "cn=Akira Shavers,ou=Administrators,ou=DomainUsers,dc=cybersecurity,dc=local" -Reset –New Password (ConvertTo-SecureString -AsPlainText "TodayisSaturday1" -Force)
