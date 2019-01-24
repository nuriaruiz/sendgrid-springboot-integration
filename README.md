# sendgrid-springboot-integration
Integration SendGrid Spring Boot


Simple configuration to test SendGrid service with Spring Boot.
Put your SendGrid api key in application.properties and run MailingdemoApplication. 

SendGridEmailService is to send mail to SendGridService. Implements EmailService.

BouncesController is a controller to get POST request from SendGrid when a bounced event occurs.
