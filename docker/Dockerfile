FROM openjdk:8u151-jdk-alpine3.7

EXPOSE 8070

ENV APP_HOME /usr/src/app

COPY target/shopping-cart-0.0.1-SNAPSHOT.jar $APP_HOME/app.jar

WORKDIR $APP_HOME

ENTRYPOINT exec java -jar app.jar


# Use an OpenJDK image for Windows Server Core
#FROM mcr.microsoft.com/openjdk/jdk:8-windowsservercore-ltsc2019

# Set environment variables
# ENV APP_HOME="C:\\app"

# # Create an application directory
# RUN mkdir %APP_HOME%

# # Copy the application JAR file
# COPY target/shopping-cart-0.0.1-SNAPSHOT.jar %APP_HOME%\\app.jar

# # Set the working directory
# WORKDIR %APP_HOME%

# # Expose port 8070
# EXPOSE 8070

# # Define the entry point to run the Java application
# ENTRYPOINT ["java", "-jar", "app.jar"]
