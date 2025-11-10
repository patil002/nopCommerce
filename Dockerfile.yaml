# Stage 1: runtime image for NopCommerce
FROM mcr.microsoft.com/dotnet/aspnet:8.0 AS base
WORKDIR /app
EXPOSE 80

# Copy the published output from the GitHub build step
COPY demo/ ./

ENTRYPOINT ["dotnet", "Nop.Web.dll"]
