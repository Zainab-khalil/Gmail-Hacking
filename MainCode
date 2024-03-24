import smtplib
from email.mime.text import MIMEText
from email.mime.multipart import MIMEMultipart

sender_email ='yourgmail'
sender_password = 'maww nixl hldw ndda'

# Set up the SMTP server and credentials
smtp_server = 'smtp.gmail.com'
smtp_port = 587  # Use the appropriate port for your SMTP server

# Create the email message
msg = MIMEMultipart()
msg['From'] = sender_email
msg['To'] = ''  # Your blocked email addresscd
msg['Subject'] = 'i can hack u bitch'
body = 'This is the body of the email.'
msg.attach(MIMEText(body, 'plain'))

email_message=msg.as_string()

# Send the email
try:
    server = smtplib.SMTP('smtp.gmail.com', 587)
    server.starttls()
    server.login('yourgmail', 'maww nixl hldw ndda')
    from_addrs=sender_emailto_addrs=['']
    server.sendmail('yourgmail','', msg.as_string())
    server.quit()
    print('Email sent successfully.')
except Exception as e:
    print(f'Error sending email: {e}')     
