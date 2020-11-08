import smtplib

server = smtplib.SMTP_SSL("smtp.gmail.com", 465)
server.login("skk369852147@gmail.com","369852147zaq#")
server.sendmail("skk369852147@gmail.com",
                "loveandhope002@gmail.com",
                "hellow world what a lovely day")
server.quit()