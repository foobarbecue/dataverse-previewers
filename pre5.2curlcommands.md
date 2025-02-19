#Example Curl Commands to register previewers for Dataverse, version <= 5.1

You should be able to cut/paste any/all of the commands below to run on your Dataverse machine:

>curl -X POST -H 'Content-type: application/json' http://localhost:8080/api/admin/externalTools -d \\
>"{
>  \\"displayName\\":\\"Read Text\\",
>  \\"description\\":\\"Read the text file.\\",
>  \\"scope\\":\\"file\\",
>  \\"type\\":\\"explore\\",
>  \\"hasPreviewMode\\":\\"true\\",
>  \\"toolUrl\\":\\"https://globaldataversecommunityconsortium.github.io/dataverse-previewers/previewers/TextPreview.html\",
>  \\"toolParameters\\": {
>      \\"queryParameters\\":[
>        {\\"fileid\\":\\"{fileId}\\"},
>        {\\"siteUrl\\":\\"{siteUrl}\\"},
>        {\\"key\\":\\"{apiToken}\\"},
>        {\\"datasetid\\":\\"{datasetId}\\"},
>        {\\"datasetversion\\":\\"{datasetVersion}\\"},
>        {\\"locale\\":\\"{localeCode}\\"}
>      ]
>    },
>  \\"contentType\\":\\"text/plain\\"
>}"

>curl -X POST -H 'Content-type: application/json' http://localhost:8080/api/admin/externalTools -d \\
>"{
>  \\"displayName\\":\\"View Html\\",
>  \\"description\\":\\"View the html file.\\",
>  \\"scope\\":\\"file\\",
>  \\"type\\":\\"explore\\",
>  \\"hasPreviewMode\\":\\"true\\",
>  \\"toolUrl\\":\\"https://globaldataversecommunityconsortium.github.io/dataverse-previewers/previewers/HtmlPreview.html\",
>  \\"toolParameters\\": {
>      \\"queryParameters\\":[
>        {\\"fileid\\":\\"{fileId}\\"},
>        {\\"siteUrl\\":\\"{siteUrl}\\"},
>        {\\"key\\":\\"{apiToken}\\"},
>        {\\"datasetid\\":\\"{datasetId}\\"},
>        {\\"datasetversion\\":\\"{datasetVersion}\\"},
>        {\\"locale\\":\\"{localeCode}\\"}
>      ]
>    },
>  \\"contentType\\":\\"text/html\\"
>}"

>curl -X POST -H 'Content-type: application/json' http://localhost:8080/api/admin/externalTools -d \\
>"{
>  \\"displayName\\":\\"Play Audio\\",
>  \\"description\\":\\"Listen to an audio file.\\",
>  \\"scope\\":\\"file\\",
>  \\"type\\":\\"explore\\",
>  \\"hasPreviewMode\\":\\"true\\",
>  \\"toolUrl\\":\\"https://globaldataversecommunityconsortium.github.io/dataverse-previewers/previewers/AudioPreview.html\",
>  \\"toolParameters\\": {
>      \\"queryParameters\\":[
>        {\\"fileid\\":\\"{fileId}\\"},
>        {\\"siteUrl\\":\\"{siteUrl}\\"},
>        {\\"key\\":\\"{apiToken}\\"},
>        {\\"datasetid\\":\\"{datasetId}\\"},
>        {\\"datasetversion\\":\\"{datasetVersion}\\"},
>        {\\"locale\\":\\"{localeCode}\\"}
>      ]
>    },
>  \\"contentType\\":\\"audio/mp3\\"
>}"

>curl -X POST -H 'Content-type: application/json' http://localhost:8080/api/admin/externalTools -d \\
>"{
>  \\"displayName\\":\\"Play Audio\\",
>  \\"description\\":\\"Listen to an audio file.\\",
>  \\"scope\\":\\"file\\",
>  \\"type\\":\\"explore\\",
>  \\"hasPreviewMode\\":\\"true\\",
>  \\"toolUrl\\":\\"https://globaldataversecommunityconsortium.github.io/dataverse-previewers/previewers/AudioPreview.html\",
>  \\"toolParameters\\": {
>      \\"queryParameters\\":[
>        {\\"fileid\\":\\"{fileId}\\"},
>        {\\"siteUrl\\":\\"{siteUrl}\\"},
>        {\\"key\\":\\"{apiToken}\\"},
>        {\\"datasetid\\":\\"{datasetId}\\"},
>        {\\"datasetversion\\":\\"{datasetVersion}\\"},
>        {\\"locale\\":\\"{localeCode}\\"}
>      ]
>    },
>  \\"contentType\\":\\"audio/mpeg\\"
>}"

>curl -X POST -H 'Content-type: application/json' http://localhost:8080/api/admin/externalTools -d \\
>"{
>  \\"displayName\\":\\"Play Audio\\",
>  \\"description\\":\\"Listen to an audio file.\\",
>  \\"scope\\":\\"file\\",
>  \\"type\\":\\"explore\\",
>  \\"hasPreviewMode\\":\\"true\\",
>  \\"toolUrl\\":\\"https://globaldataversecommunityconsortium.github.io/dataverse-previewers/previewers/AudioPreview.html\",
>  \\"toolParameters\\": {
>      \\"queryParameters\\":[
>        {\\"fileid\\":\\"{fileId}\\"},
>        {\\"siteUrl\\":\\"{siteUrl}\\"},
>        {\\"key\\":\\"{apiToken}\\"},
>        {\\"datasetid\\":\\"{datasetId}\\"},
>        {\\"datasetversion\\":\\"{datasetVersion}\\"},
>        {\\"locale\\":\\"{localeCode}\\"}
>      ]
>    },
>  \\"contentType\\":\\"audio/wav\\"
>}"

>curl -X POST -H 'Content-type: application/json' http://localhost:8080/api/admin/externalTools -d \\
>"{
>  \\"displayName\\":\\"Play Audio\\",
>  \\"description\\":\\"Listen to an audio file.\\",
>  \\"scope\\":\\"file\\",
>  \\"type\\":\\"explore\\",
>  \\"hasPreviewMode\\":\\"true\\",
>  \\"toolUrl\\":\\"https://globaldataversecommunityconsortium.github.io/dataverse-previewers/previewers/AudioPreview.html\",
>  \\"toolParameters\\": {
>      \\"queryParameters\\":[
>        {\\"fileid\\":\\"{fileId}\\"},
>        {\\"siteUrl\\":\\"{siteUrl}\\"},
>        {\\"key\\":\\"{apiToken}\\"},
>        {\\"datasetid\\":\\"{datasetId}\\"},
>        {\\"datasetversion\\":\\"{datasetVersion}\\"},
>        {\\"locale\\":\\"{localeCode}\\"}
>      ]
>    },
>  \\"contentType\\":\\"audio/ogg\\"
>}"

>curl -X POST -H 'Content-type: application/json' http://localhost:8080/api/admin/externalTools -d \\
>"{
>  \\"displayName\\":\\"View Image\\",
>  \\"description\\":\\"Preview an image file.\\",
>  \\"scope\\":\\"file\\",
>  \\"type\\":\\"explore\\",
>  \\"hasPreviewMode\\":\\"true\\",
>  \\"toolUrl\\":\\"https://globaldataversecommunityconsortium.github.io/dataverse-previewers/previewers/ImagePreview.html\",
>  \\"toolParameters\\": {
>      \\"queryParameters\\":[
>        {\\"fileid\\":\\"{fileId}\\"},
>        {\\"siteUrl\\":\\"{siteUrl}\\"},
>        {\\"key\\":\\"{apiToken}\\"},
>        {\\"datasetid\\":\\"{datasetId}\\"},
>        {\\"datasetversion\\":\\"{datasetVersion}\\"},
>        {\\"locale\\":\\"{localeCode}\\"}
>      ]
>    },
>  \\"contentType\\":\\"image/gif\\"
>}"

>curl -X POST -H 'Content-type: application/json' http://localhost:8080/api/admin/externalTools -d \\
>"{
>  \\"displayName\\":\\"View Image\\",
>  \\"description\\":\\"Preview an image file.\\",
>  \\"scope\\":\\"file\\",
>  \\"type\\":\\"explore\\",
>  \\"hasPreviewMode\\":\\"true\\",
>  \\"toolUrl\\":\\"https://globaldataversecommunityconsortium.github.io/dataverse-previewers/previewers/ImagePreview.html\",
>  \\"toolParameters\\": {
>      \\"queryParameters\\":[
>        {\\"fileid\\":\\"{fileId}\\"},
>        {\\"siteUrl\\":\\"{siteUrl}\\"},
>        {\\"key\\":\\"{apiToken}\\"},
>        {\\"datasetid\\":\\"{datasetId}\\"},
>        {\\"datasetversion\\":\\"{datasetVersion}\\"},
>        {\\"locale\\":\\"{localeCode}\\"}
>      ]
>    },
>  \\"contentType\\":\\"image/jpeg\\"
>}"

>curl -X POST -H 'Content-type: application/json' http://localhost:8080/api/admin/externalTools -d \\
>"{
>  \\"displayName\\":\\"View Image\\",
>  \\"description\\":\\"Preview an image file.\\",
>  \\"scope\\":\\"file\\",
>  \\"type\\":\\"explore\\",
>  \\"hasPreviewMode\\":\\"true\\",
>  \\"toolUrl\\":\\"https://globaldataversecommunityconsortium.github.io/dataverse-previewers/previewers/ImagePreview.html\",
>  \\"toolParameters\\": {
>      \\"queryParameters\\":[
>        {\\"fileid\\":\\"{fileId}\\"},
>        {\\"siteUrl\\":\\"{siteUrl}\\"},
>        {\\"key\\":\\"{apiToken}\\"},
>        {\\"datasetid\\":\\"{datasetId}\\"},
>        {\\"datasetversion\\":\\"{datasetVersion}\\"},
>        {\\"locale\\":\\"{localeCode}\\"}
>      ]
>    },
>  \\"contentType\\":\\"image/png\\"
>}"

>curl -X POST -H 'Content-type: application/json' http://localhost:8080/api/admin/externalTools -d \\
>"{
>  \\"displayName\\":\\"Read Document\\",
>  \\"description\\":\\"Read a pdf document.\\",
>  \\"scope\\":\\"file\\",
>  \\"type\\":\\"explore\\",
>  \\"hasPreviewMode\\":\\"true\\",
>  \\"toolUrl\\":\\"https://globaldataversecommunityconsortium.github.io/dataverse-previewers/previewers/PDFPreview.html\",
>  \\"toolParameters\\": {
>      \\"queryParameters\\":[
>        {\\"fileid\\":\\"{fileId}\\"},
>        {\\"siteUrl\\":\\"{siteUrl}\\"},
>        {\\"key\\":\\"{apiToken}\\"},
>        {\\"datasetid\\":\\"{datasetId}\\"},
>        {\\"datasetversion\\":\\"{datasetVersion}\\"},
>        {\\"locale\\":\\"{localeCode}\\"}
>      ]
>    },
>  \\"contentType\\":\\"application/pdf\\"
>}"

>curl -X POST -H 'Content-type: application/json' http://localhost:8080/api/admin/externalTools -d \\
>"{
>  \\"displayName\\":\\"Play Video\\",
>  \\"description\\":\\"Watch a video file.\\",
>  \\"scope\\":\\"file\\",
>  \\"type\\":\\"explore\\",
>  \\"hasPreviewMode\\":\\"true\\",
>  \\"toolUrl\\":\\"https://globaldataversecommunityconsortium.github.io/dataverse-previewers/previewers/VideoPreview.html\",
>  \\"toolParameters\\": {
>      \\"queryParameters\\":[
>        {\\"fileid\\":\\"{fileId}\\"},
>        {\\"siteUrl\\":\\"{siteUrl}\\"},
>        {\\"key\\":\\"{apiToken}\\"},
>        {\\"datasetid\\":\\"{datasetId}\\"},
>        {\\"datasetversion\\":\\"{datasetVersion}\\"},
>        {\\"locale\\":\\"{localeCode}\\"}
>      ]
>    },
>  \\"contentType\\":\\"video/mp4\\"
>}"

>curl -X POST -H 'Content-type: application/json' http://localhost:8080/api/admin/externalTools -d \\
>"{
>  \\"displayName\\":\\"Play Video\\",
>  \\"description\\":\\"Watch a video file.\\",
>  \\"scope\\":\\"file\\",
>  \\"type\\":\\"explore\\",
>  \\"hasPreviewMode\\":\\"true\\",
>  \\"toolUrl\\":\\"https://globaldataversecommunityconsortium.github.io/dataverse-previewers/previewers/VideoPreview.html\",
>  \\"toolParameters\\": {
>      \\"queryParameters\\":[
>        {\\"fileid\\":\\"{fileId}\\"},
>        {\\"siteUrl\\":\\"{siteUrl}\\"},
>        {\\"key\\":\\"{apiToken}\\"},
>        {\\"datasetid\\":\\"{datasetId}\\"},
>        {\\"datasetversion\\":\\"{datasetVersion}\\"},
>        {\\"locale\\":\\"{localeCode}\\"}
>      ]
>    },
>  \\"contentType\\":\\"video/ogg\\"
>}"

>curl -X POST -H 'Content-type: application/json' http://localhost:8080/api/admin/externalTools -d \\
>"{
>  \\"displayName\\":\\"Play Video\\",
>  \\"description\\":\\"Watch a video file.\\",
>  \\"scope\\":\\"file\\",
>  \\"type\\":\\"explore\\",
>  \\"hasPreviewMode\\":\\"true\\",
>  \\"toolUrl\\":\\"https://globaldataversecommunityconsortium.github.io/dataverse-previewers/previewers/VideoPreview.html\",
>  \\"toolParameters\\": {
>      \\"queryParameters\\":[
>        {\\"fileid\\":\\"{fileId}\\"},
>        {\\"siteUrl\\":\\"{siteUrl}\\"},
>        {\\"key\\":\\"{apiToken}\\"},
>        {\\"datasetid\\":\\"{datasetId}\\"},
>        {\\"datasetversion\\":\\"{datasetVersion}\\"},
>        {\\"locale\\":\\"{localeCode}\\"}
>      ]
>    },
>  \\"contentType\\":\\"video/quicktime\\"
>}"

>curl -X POST -H 'Content-type: application/json' http://localhost:8080/api/admin/externalTools -d \\
>"{
>  \\"displayName\\":\\"View Data\\",
>  \\"description\\":\\"View the spreadsheet data.\\",
>  \\"scope\\":\\"file\\",
>  \\"type\\":\\"explore\\",
>  \\"hasPreviewMode\\":\\"true\\",
>  \\"toolUrl\\":\\"https://globaldataversecommunityconsortium.github.io/dataverse-previewers/previewers/SpreadsheetPreview.html\",
>  \\"toolParameters\\": {
>      \\"queryParameters\\":[
>        {\\"fileid\\":\\"{fileId}\\"},
>        {\\"siteUrl\\":\\"{siteUrl}\\"},
>        {\\"key\\":\\"{apiToken}\\"},
>        {\\"datasetid\\":\\"{datasetId}\\"},
>        {\\"datasetversion\\":\\"{datasetVersion}\\"},
>        {\\"locale\\":\\"{localeCode}\\"}
>      ]
>    },
>  \\"contentType\\":\\"text/comma-separated-values\\"
>}"

>curl -X POST -H 'Content-type: application/json' http://localhost:8080/api/admin/externalTools -d \\
>"{
>  \\"displayName\\":\\"View Data\\",
>  \\"description\\":\\"View the spreadsheet data.\\",
>  \\"scope\\":\\"file\\",
>  \\"type\\":\\"explore\\",
>  \\"hasPreviewMode\\":\\"true\\",
>  \\"toolUrl\\":\\"https://globaldataversecommunityconsortium.github.io/dataverse-previewers/previewers/SpreadsheetPreview.html\",
>  \\"toolParameters\\": {
>      \\"queryParameters\\":[
>        {\\"fileid\\":\\"{fileId}\\"},
>        {\\"siteUrl\\":\\"{siteUrl}\\"},
>        {\\"key\\":\\"{apiToken}\\"},
>        {\\"datasetid\\":\\"{datasetId}\\"},
>        {\\"datasetversion\\":\\"{datasetVersion}\\"},
>        {\\"locale\\":\\"{localeCode}\\"}
>      ]
>    },
>  \\"contentType\\":\\"text/tab-separated-values\\"
>}"

>curl -X POST -H 'Content-type: application/json' http://localhost:8080/api/admin/externalTools -d \\
>"{
>  \\"displayName\\":\\"View Data\\",
>  \\"description\\":\\"View the spreadsheet data.\\",
>  \\"scope\\":\\"file\\",
>  \\"type\\":\\"explore\\",
>  \\"hasPreviewMode\\":\\"true\\",
>  \\"toolUrl\\":\\"https://globaldataversecommunityconsortium.github.io/dataverse-previewers/previewers/SpreadsheetPreview.html\",
>  \\"toolParameters\\": {
>      \\"queryParameters\\":[
>        {\\"fileid\\":\\"{fileId}\\"},
>        {\\"siteUrl\\":\\"{siteUrl}\\"},
>        {\\"key\\":\\"{apiToken}\\"},
>        {\\"datasetid\\":\\"{datasetId}\\"},
>        {\\"datasetversion\\":\\"{datasetVersion}\\"},
>        {\\"locale\\":\\"{localeCode}\\"}
>      ]
>    },
>  \\"contentType\\":\\"text/csv\\"
>}"

>curl -X POST -H 'Content-type: application/json' http://localhost:8080/api/admin/externalTools -d \\
>"{
>  \\"displayName\\":\\"View Data\\",
>  \\"description\\":\\"View the spreadsheet data.\\",
>  \\"scope\\":\\"file\\",
>  \\"type\\":\\"explore\\",
>  \\"hasPreviewMode\\":\\"true\\",
>  \\"toolUrl\\":\\"https://globaldataversecommunityconsortium.github.io/dataverse-previewers/previewers/SpreadsheetPreview.html\",
>  \\"toolParameters\\": {
>      \\"queryParameters\\":[
>        {\\"fileid\\":\\"{fileId}\\"},
>        {\\"siteUrl\\":\\"{siteUrl}\\"},
>        {\\"key\\":\\"{apiToken}\\"},
>        {\\"datasetid\\":\\"{datasetId}\\"},
>        {\\"datasetversion\\":\\"{datasetVersion}\\"},
>        {\\"locale\\":\\"{localeCode}\\"}
>      ]
>    },
>  \\"contentType\\":\\"text/tsv\\"
>}"


>curl -X POST -H 'Content-type: application/json' http://localhost:8080/api/admin/externalTools -d \\
>"{
>  \\"displayName\\":\\"View Stata File\\",
>  \\"description\\":\\"View the Stata file as text.\\",
>  \\"scope\\":\\"file\\",
>  \\"type\\":\\"explore\\",
>  \\"hasPreviewMode\\":\\"true\\",
>  \\"toolUrl\\":\\"https://globaldataversecommunityconsortium.github.io/dataverse-previewers/previewers/TextPreview.html\",
>  \\"toolParameters\\": {
>      \\"queryParameters\\":[
>        {\\"fileid\\":\\"{fileId}\\"},
>        {\\"siteUrl\\":\\"{siteUrl}\\"},
>        {\\"key\\":\\"{apiToken}\\"},
>        {\\"datasetid\\":\\"{datasetId}\\"},
>        {\\"datasetversion\\":\\"{datasetVersion}\\"},
>        {\\"locale\\":\\"{localeCode}\\"}
>      ]
>    },
>  \\"contentType\\":\\"application/x-stata-syntax\\"
>}"

>curl -X POST -H 'Content-type: application/json' http://localhost:8080/api/admin/externalTools -d \\
>"{
>  \\"displayName\\":\\"View R file\\",
>  \\"description\\":\\"View the R file as text.\\",
>  \\"scope\\":\\"file\\",
>  \\"type\\":\\"explore\\",
>  \\"hasPreviewMode\\":\\"true\\",
>  \\"toolUrl\\":\\"https://globaldataversecommunityconsortium.github.io/dataverse-previewers/previewers/TextPreview.html\",
>  \\"toolParameters\\": {
>      \\"queryParameters\\":[
>        {\\"fileid\\":\\"{fileId}\\"},
>        {\\"siteUrl\\":\\"{siteUrl}\\"},
>        {\\"key\\":\\"{apiToken}\\"},
>        {\\"datasetid\\":\\"{datasetId}\\"},
>        {\\"datasetversion\\":\\"{datasetVersion}\\"},
>        {\\"locale\\":\\"{localeCode}\\"}
>      ]
>    },
>  \\"contentType\\":\\"type/x-r-syntax\\"
>}"

>curl -X POST -H 'Content-type: application/json' http://localhost:8080/api/admin/externalTools -d \\
>"{
>  \\"displayName\\":\\"View Annotations\\",
>  \\"description\\":\\"View the annotation entries in a file.\\",
>  \\"scope\\":\\"file\\",
>  \\"type\\":\\"explore\\",
>  \\"hasPreviewMode\\":\\"true\\",
>  \\"toolUrl\\":\\"https://globaldataversecommunityconsortium.github.io/dataverse-previewers/previewers/HypothesisPreview.html\",
>  \\"toolParameters\\": {
>      \\"queryParameters\\":[
>        {\\"fileid\\":\\"{fileId}\\"},
>        {\\"siteUrl\\":\\"{siteUrl}\\"},
>        {\\"key\\":\\"{apiToken}\\"},
>        {\\"datasetid\\":\\"{datasetId}\\"},
>        {\\"datasetversion\\":\\"{datasetVersion}\\"},
>        {\\"locale\\":\\"{localeCode}\\"}
>      ]
>    },
>  \\"contentType\\":\\"application/x-json-hypothesis\\"
>}"

