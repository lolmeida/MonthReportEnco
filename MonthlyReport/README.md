gcloud builds submit --tag gcr.io/encostreamlitreport/encostreamlitreport --project=encostreamlitreport

cloud run deploy --image qcr.io/encostreamlitreport/encostreamlitreport --platform managed --project=encostreamlitreport --allow-unauthenticated