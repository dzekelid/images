---
swagger: "2.0"
x-collection-name: ConvertAPI
x-complete: 0
info:
  title: Convert API Email to Image
  description: The API for converting E-Mail files to PDF files and Images. These
    file formats eml, mbx, msg, oft can be converted to png, jpg, tif.
  version: v1
host: do.convertapi.com
basePath: /
schemes:
- http
produces:
- application/json
consumes:
- application/json
paths:
  /Email2Image:
    post:
      summary: Email to Image
      description: The API for converting E-Mail files to PDF files and Images. These
        file formats eml, mbx, msg, oft can be converted to png, jpg, tif.
      operationId: email2image
      x-api-path-slug: email2image-post
      parameters:
      - in: query
        name: ApiKey
        description: API Key should be passed if you purchased membership with credits
      - in: query
        name: File
        description: 'Supported source file formats: eml, mbx, msg, oft'
      - in: query
        name: ImageResolutionH
        description: Image horizontal resolution (DPI)
      - in: query
        name: ImageResolutionV
        description: Image vertical resolution (DPI)
      - in: query
        name: JpgQuality
        description: Jpg image quality
      - in: query
        name: OutputFormat
        description: Supported output file formats png, jpg, tif
      - in: query
        name: StoreFile
        description: Store file on server and return url to file instead of file stream
          response
      - in: query
        name: Timeout
        description: Conversion timeout in seconds
      responses:
        200:
          description: OK
      tags:
      - Email
      - Image
  /Excel2Image:
    post:
      summary: Excel to Image
      description: The API for converting Excel documents to PDF files and Images.
        These file formats csv, xls, xlsb, xlsx, xlt, xltx can be converted to png,
        jpg, tif.
      operationId: excel2image
      x-api-path-slug: excel2image-post
      parameters:
      - in: query
        name: AlternativeParser
        description: If some objects are missing in converted Pdf files from original
          source files this option can be enabled to improve conversion
      - in: query
        name: ApiKey
        description: API Key should be passed if you purchased membership with credits
      - in: query
        name: File
        description: 'Supported source file formats: csv, xls, xlsb, xlsx, xlt, xltx'
      - in: query
        name: ImageResolutionH
        description: Image horizontal resolution (DPI)
      - in: query
        name: ImageResolutionV
        description: Image vertical resolution (DPI)
      - in: query
        name: JpgQuality
        description: Jpg image quality
      - in: query
        name: OutputFormat
        description: Supported output file formats png, jpg, tif
      - in: query
        name: StoreFile
        description: Store file on server and return url to file instead of file stream
          response
      - in: query
        name: Timeout
        description: Conversion timeout in seconds
      - in: query
        name: WorksheetActive
        description: Set to convert active worksheet
      - in: query
        name: WorksheetIndex
        description: Set worksheet index(number) to convert
      - in: query
        name: WorksheetName
        description: Set worksheet name to convert
      responses:
        200:
          description: OK
      tags:
      - Excel
      - Image
  /Image2Image:
    post:
      summary: Image to Image
      description: The API for converting Image files to PDF files and Images. These
        file formats avs, bmp, dcx, dib, dpx, fax, fits, fpx, gif, ico, iptc, jbig,
        jp2, jpeg, jpg, mdi, miff, mng, mpc, mtv, otb, pbm, pcd, pcds, pct, pcx, pgm,
        pict, png, pnm, ppm, psd, p7, ras, rgba, sun, tga, tiff, tif, vicar, vid,
        viff, wmf, xbm, xpm, xwd can be converted to png, jpg, tif.
      operationId: image2image
      x-api-path-slug: image2image-post
      parameters:
      - in: query
        name: ApiKey
        description: API Key should be passed if you purchased membership with credits
      - in: query
        name: File
        description: 'Supported source file formats: avs, bmp, dcx, dib, dpx, fax,
          fits, fpx, gif, ico, iptc, jbig, jp2, jpeg, jpg, mdi, miff, mng, mpc, mtv,
          otb, pbm, pcd, pcds, pct, pcx, pgm, pict, png, pnm, ppm, psd, p7, ras, rgba,
          sun, tga, tiff, tif, vicar, vid, viff, wmf, xbm, xpm, xwd'
      - in: query
        name: ImageResolutionH
        description: Image horizontal resolution (DPI)
      - in: query
        name: ImageResolutionV
        description: Image vertical resolution (DPI)
      - in: query
        name: JpgQuality
        description: Jpg image quality
      - in: query
        name: OutputFormat
        description: Supported output file formats png, jpg, tif
      - in: query
        name: StoreFile
        description: Store file on server and return url to file instead of file stream
          response
      - in: query
        name: Timeout
        description: Conversion timeout in seconds
      responses:
        200:
          description: OK
      tags:
      - Image
      - Image
  /Image2Pdf:
    post:
      summary: Image to PDF
      description: The API for converting Image files to PDF files and Images. These
        file formats avs, bmp, dcx, dib, dpx, fax, fits, fpx, gif, ico, iptc, jbig,
        jp2, jpeg, jpg, mdi, miff, mng, mpc, mtv, otb, pbm, pcd, pcds, pct, pcx, pgm,
        pict, png, pnm, ppm, psd, p7, ras, rgba, sun, tga, tiff, tif, vicar, vid,
        viff, wmf, xbm, xpm, xwd can be converted to pdf, pdfa, png, jpg, tif.
      operationId: image2pdf
      x-api-path-slug: image2pdf-post
      parameters:
      - in: query
        name: ApiKey
        description: API Key should be passed if you purchased membership with credits
      - in: query
        name: DocumentAuthor
        description: Set the author of the generated Pdf file
      - in: query
        name: DocumentKeywords
        description: Set the keywords of the generated Pdf file
      - in: query
        name: DocumentSubject
        description: Set the subject of the generated Pdf file
      - in: query
        name: DocumentTitle
        description: Set the title of the generated Pdf file
      - in: query
        name: File
        description: 'Supported source file formats: avs, bmp, dcx, dib, dpx, fax,
          fits, fpx, gif, ico, iptc, jbig, jp2, jpeg, jpg, mdi, miff, mng, mpc, mtv,
          otb, pbm, pcd, pcds, pct, pcx, pgm, pict, png, pnm, ppm, psd, p7, ras, rgba,
          sun, tga, tiff, tif, vicar, vid, viff, wmf, xbm, xpm, xwd'
      - in: query
        name: Ocr
        description: Apply optical character recognition (OCR) and convert scanned
          text images into editable and searchable PDF
      - in: query
        name: OutputFormat
        description: Supported output file formats pdf, pdfa, png, jpg, tif
      - in: query
        name: StoreFile
        description: Store file on server and return url to file instead of file stream
          response
      - in: query
        name: Timeout
        description: Conversion timeout in seconds
      responses:
        200:
          description: OK
      tags:
      - Image
      - PDF
  /Journal2Image:
    post:
      summary: Journal to Image
      description: The API for converting Windows Journal Viewer documents to PDF
        files and Images. These file formats jnt can be converted to png, jpg, tif.
      operationId: journal2image
      x-api-path-slug: journal2image-post
      parameters:
      - in: query
        name: ApiKey
        description: API Key should be passed if you purchased membership with credits
      - in: query
        name: File
        description: 'Supported source file formats: jnt'
      - in: query
        name: ImageResolutionH
        description: Image horizontal resolution (DPI)
      - in: query
        name: ImageResolutionV
        description: Image vertical resolution (DPI)
      - in: query
        name: JpgQuality
        description: Jpg image quality
      - in: query
        name: OutputFormat
        description: Supported output file formats png, jpg, tif
      - in: query
        name: StoreFile
        description: Store file on server and return url to file instead of file stream
          response
      - in: query
        name: Timeout
        description: Conversion timeout in seconds
      responses:
        200:
          description: OK
      tags:
      - Journal
      - Image
  /Lotus2Image:
    post:
      summary: Lotus to Image
      description: The API for converting Lotus Smart Suite documents to PDF files
        and Images. These file formats 123, 12m, wk1, wk2, wk3, lwp, mwp, sam can
        be converted to png, jpg, tif.
      operationId: lotus2image
      x-api-path-slug: lotus2image-post
      parameters:
      - in: query
        name: ApiKey
        description: API Key should be passed if you purchased membership with credits
      - in: query
        name: File
        description: 'Supported source file formats: 123, 12m, wk1, wk2, wk3, lwp,
          mwp, sam'
      - in: query
        name: ImageResolutionH
        description: Image horizontal resolution (DPI)
      - in: query
        name: ImageResolutionV
        description: Image vertical resolution (DPI)
      - in: query
        name: JpgQuality
        description: Jpg image quality
      - in: query
        name: OutputFormat
        description: Supported output file formats png, jpg, tif
      - in: query
        name: StoreFile
        description: Store file on server and return url to file instead of file stream
          response
      - in: query
        name: Timeout
        description: Conversion timeout in seconds
      responses:
        200:
          description: OK
      tags:
      - Lotus
      - Image
  /OpenOffice2Image:
    post:
      summary: Open Office to Image
      description: The API for converting OpenOffice documents to PDF files and Images.
        These file formats mml, odc, odf, odg, odi, odm, odp, ods, odt, otg, oth,
        otp, ots, pxl, sgl, smf, srw, stc, sti, stw, sxc, sxg, sxi, sxm, sxw, vor,
        wv2 can be converted to png, jpg, tif.
      operationId: openoffice2image
      x-api-path-slug: openoffice2image-post
      parameters:
      - in: query
        name: AlternativeParser
        description: If some objects are missing in converted Pdf files from original
          source files this option can be enabled to improve conversion
      - in: query
        name: ApiKey
        description: API Key should be passed if you purchased membership with credits
      - in: query
        name: File
        description: 'Supported source file formats: mml, odc, odf, odg, odi, odm,
          odp, ods, odt, otg, oth, otp, ots, pxl, sgl, smf, srw, stc, sti, stw, sxc,
          sxg, sxi, sxm, sxw, vor, wv2'
      - in: query
        name: ImageResolutionH
        description: Image horizontal resolution (DPI)
      - in: query
        name: ImageResolutionV
        description: Image vertical resolution (DPI)
      - in: query
        name: JpgQuality
        description: Jpg image quality
      - in: query
        name: OutputFormat
        description: Supported output file formats png, jpg, tif
      - in: query
        name: StoreFile
        description: Store file on server and return url to file instead of file stream
          response
      - in: query
        name: Timeout
        description: Conversion timeout in seconds
      responses:
        200:
          description: OK
      tags:
      - Open
      - Office
      - Image
  /Pdf2Image:
    post:
      summary: PDF to Image
      description: The API for converting PDF documents to Image. These file formats
        pdf can be converted to png, jpg, tif.
      operationId: pdf2image
      x-api-path-slug: pdf2image-post
      parameters:
      - in: query
        name: ApiKey
        description: API Key should be passed if you purchased membership with credits
      - in: query
        name: File
        description: 'Supported source file formats: pdf'
      - in: query
        name: ImageResolutionH
        description: Image horizontal resolution (DPI)
      - in: query
        name: ImageResolutionV
        description: Image vertical resolution (DPI)
      - in: query
        name: JpgQuality
        description: Jpg image quality
      - in: query
        name: OutputFormat
        description: Supported output file formats png, jpg, tif
      - in: query
        name: StoreFile
        description: Store file on server and return url to file instead of file stream
          response
      - in: query
        name: Timeout
        description: Conversion timeout in seconds
      responses:
        200:
          description: OK
      tags:
      - PDF
      - Image
  /PostScript2Image:
    post:
      summary: Post Script to Image
      description: The API for converting PostScript files to PDF files and Images.
        These file formats ps, eps, prn can be converted to png, jpg, tif.
      operationId: postscript2image
      x-api-path-slug: postscript2image-post
      parameters:
      - in: query
        name: ApiKey
        description: API Key should be passed if you purchased membership with credits
      - in: query
        name: File
        description: 'Supported source file formats: ps, eps, prn'
      - in: query
        name: ImageResolutionH
        description: Image horizontal resolution (DPI)
      - in: query
        name: ImageResolutionV
        description: Image vertical resolution (DPI)
      - in: query
        name: JpgQuality
        description: Jpg image quality
      - in: query
        name: OutputFormat
        description: Supported output file formats png, jpg, tif
      - in: query
        name: StoreFile
        description: Store file on server and return url to file instead of file stream
          response
      - in: query
        name: Timeout
        description: Conversion timeout in seconds
      responses:
        200:
          description: OK
      tags:
      - Script
      - Image
  /PowerPoint2Image:
    post:
      summary: Power Point to Image
      description: The API for converting PowerPoint documents to PDF files and Images.
        These file formats pot, potx, pps, ppsx, ppt, pptx can be converted to png,
        jpg, tif.
      operationId: powerpoint2image
      x-api-path-slug: powerpoint2image-post
      parameters:
      - in: query
        name: AlternativeParser
        description: If some objects are missing in converted Pdf files from original
          source files this option can be enabled to improve conversion
      - in: query
        name: ApiKey
        description: API Key should be passed if you purchased membership with credits
      - in: query
        name: File
        description: 'Supported source file formats: pot, potx, pps, ppsx, ppt, pptx'
      - in: query
        name: ImageResolutionH
        description: Image horizontal resolution (DPI)
      - in: query
        name: ImageResolutionV
        description: Image vertical resolution (DPI)
      - in: query
        name: JpgQuality
        description: Jpg image quality
      - in: query
        name: OutputFormat
        description: Supported output file formats png, jpg, tif
      - in: query
        name: StoreFile
        description: Store file on server and return url to file instead of file stream
          response
      - in: query
        name: Timeout
        description: Conversion timeout in seconds
      responses:
        200:
          description: OK
      tags:
      - Power
      - Point
      - Image
  /Project2Image:
    post:
      summary: Project to Image
      description: The API for converting Project documents to PDF files and Images.
        These file formats mpp, mpt can be converted to png, jpg, tif.
      operationId: project2image
      x-api-path-slug: project2image-post
      parameters:
      - in: query
        name: ApiKey
        description: API Key should be passed if you purchased membership with credits
      - in: query
        name: File
        description: 'Supported source file formats: mpp, mpt'
      - in: query
        name: ImageResolutionH
        description: Image horizontal resolution (DPI)
      - in: query
        name: ImageResolutionV
        description: Image vertical resolution (DPI)
      - in: query
        name: JpgQuality
        description: Jpg image quality
      - in: query
        name: OutputFormat
        description: Supported output file formats png, jpg, tif
      - in: query
        name: StoreFile
        description: Store file on server and return url to file instead of file stream
          response
      - in: query
        name: Timeout
        description: Conversion timeout in seconds
      responses:
        200:
          description: OK
      tags:
      - Project
      - Image
  /Publisher2Image:
    post:
      summary: Publisher to Image
      description: The API for converting Publisher documents to PDF files and Images.
        These file formats pub can be converted to png, jpg, tif.
      operationId: publisher2image
      x-api-path-slug: publisher2image-post
      parameters:
      - in: query
        name: AlternativeParser
        description: If some objects are missing in converted Pdf files from original
          source files this option can be enabled to improve conversion
      - in: query
        name: ApiKey
        description: API Key should be passed if you purchased membership with credits
      - in: query
        name: File
        description: 'Supported source file formats: pub'
      - in: query
        name: ImageResolutionH
        description: Image horizontal resolution (DPI)
      - in: query
        name: ImageResolutionV
        description: Image vertical resolution (DPI)
      - in: query
        name: JpgQuality
        description: Jpg image quality
      - in: query
        name: OutputFormat
        description: Supported output file formats png, jpg, tif
      - in: query
        name: StoreFile
        description: Store file on server and return url to file instead of file stream
          response
      - in: query
        name: Timeout
        description: Conversion timeout in seconds
      responses:
        200:
          description: OK
      tags:
      - Publisher
      - Image
  /RichText2Image:
    post:
      summary: Rich Text to Image
      description: The API for converting Rich Text documents to PDF files and Images.
        These file formats rtf can be converted to png, jpg, tif.
      operationId: richtext2image
      x-api-path-slug: richtext2image-post
      parameters:
      - in: query
        name: ApiKey
        description: API Key should be passed if you purchased membership with credits
      - in: query
        name: File
        description: 'Supported source file formats: rtf'
      - in: query
        name: ImageResolutionH
        description: Image horizontal resolution (DPI)
      - in: query
        name: ImageResolutionV
        description: Image vertical resolution (DPI)
      - in: query
        name: JpgQuality
        description: Jpg image quality
      - in: query
        name: OutputFormat
        description: Supported output file formats png, jpg, tif
      - in: query
        name: StoreFile
        description: Store file on server and return url to file instead of file stream
          response
      - in: query
        name: Timeout
        description: Conversion timeout in seconds
      responses:
        200:
          description: OK
      tags:
      - Rich
      - Text
      - Image
  /SnapShot2Image:
    post:
      summary: Snap Shot to Image
      description: The API for converting Access Report Snapshots documents to PDF
        files and Images. These file formats snp can be converted to png, jpg, tif.
      operationId: snapshot2image
      x-api-path-slug: snapshot2image-post
      parameters:
      - in: query
        name: ApiKey
        description: API Key should be passed if you purchased membership with credits
      - in: query
        name: File
        description: 'Supported source file formats: snp'
      - in: query
        name: ImageResolutionH
        description: Image horizontal resolution (DPI)
      - in: query
        name: ImageResolutionV
        description: Image vertical resolution (DPI)
      - in: query
        name: JpgQuality
        description: Jpg image quality
      - in: query
        name: OutputFormat
        description: Supported output file formats png, jpg, tif
      - in: query
        name: StoreFile
        description: Store file on server and return url to file instead of file stream
          response
      - in: query
        name: Timeout
        description: Conversion timeout in seconds
      responses:
        200:
          description: OK
      tags:
      - Snap
      - Shot
      - Image
  /Text2Image:
    post:
      summary: Text to Image
      description: The API for converting Textual files to PDF files and Images. These
        file formats txt, log can be converted to png, jpg, tif.
      operationId: text2image
      x-api-path-slug: text2image-post
      parameters:
      - in: query
        name: ApiKey
        description: API Key should be passed if you purchased membership with credits
      - in: query
        name: File
        description: 'Supported source file formats: txt, log'
      - in: query
        name: ImageResolutionH
        description: Image horizontal resolution (DPI)
      - in: query
        name: ImageResolutionV
        description: Image vertical resolution (DPI)
      - in: query
        name: JpgQuality
        description: Jpg image quality
      - in: query
        name: OutputFormat
        description: Supported output file formats png, jpg, tif
      - in: query
        name: StoreFile
        description: Store file on server and return url to file instead of file stream
          response
      - in: query
        name: Timeout
        description: Conversion timeout in seconds
      responses:
        200:
          description: OK
      tags:
      - Text
      - Image
  /Visio2Image:
    post:
      summary: Visio to Image
      description: The API for converting Visio documents to PDF files and Images.
        These file formats vsd, vst, vsdx, vstx can be converted to png, jpg, tif.
      operationId: visio2image
      x-api-path-slug: visio2image-post
      parameters:
      - in: query
        name: AlternativeParser
        description: If some objects are missing in converted Pdf files from original
          source files this option can be enabled to improve conversion
      - in: query
        name: ApiKey
        description: API Key should be passed if you purchased membership with credits
      - in: query
        name: File
        description: 'Supported source file formats: vsd, vst, vsdx, vstx'
      - in: query
        name: ImageResolutionH
        description: Image horizontal resolution (DPI)
      - in: query
        name: ImageResolutionV
        description: Image vertical resolution (DPI)
      - in: query
        name: JpgQuality
        description: Jpg image quality
      - in: query
        name: OutputFormat
        description: Supported output file formats png, jpg, tif
      - in: query
        name: StoreFile
        description: Store file on server and return url to file instead of file stream
          response
      - in: query
        name: Timeout
        description: Conversion timeout in seconds
      responses:
        200:
          description: OK
      tags:
      - Visio
      - Image
  /Web2Image:
    post:
      summary: Web to Image
      description: The API for converting Web Pages to Images.
      operationId: web2image
      x-api-path-slug: web2image-post
      parameters:
      - in: query
        name: AcceptLanguage
        description: Set accept language header
      - in: query
        name: AlternativeParser
        description: Set alternative parser
      - in: query
        name: ApiKey
        description: API Key should be passed if you purchased membership with credits
      - in: query
        name: AuthPassword
        description: HTTP Authentication password, used if conversion web page is
          protected with HTTP authentication
      - in: query
        name: AuthUsername
        description: HTTP authentication username, used if conversion web page is
          protected with HTTP authentication
      - in: query
        name: ConversionDelay
        description: Delay in seconds before page load and PDF creation
      - in: query
        name: CUrl
        description: URI of a web page to convert
      - in: query
        name: PageHeight
        description: Set screen height
      - in: query
        name: PageWidth
        description: Set screen width
      - in: query
        name: Plugins
        description: Enable plugins such as flash
      - in: query
        name: Scripts
        description: Allow web pages to run javascript
      - in: query
        name: StoreFile
        description: Store file on server and return url to file instead of file stream
          response
      - in: query
        name: Timeout
        description: Conversion timeout in seconds
      - in: query
        name: UserAgent
        description: Set custom user agent
      responses:
        200:
          description: OK
      tags:
      - Web
      - Image
  /Word2Image:
    post:
      summary: Word to Image
      description: The API for converting Word documents to PDF files and Images.
        These file formats doc, docx, dot, dotx, wpd, wps, wri can be converted to
        png, jpg, tif.
      operationId: word2image
      x-api-path-slug: word2image-post
      parameters:
      - in: query
        name: AlternativeParser
        description: If some objects are missing in converted Pdf files from original
          source files this option can be enabled to improve conversion
      - in: query
        name: ApiKey
        description: API Key should be passed if you purchased membership with credits
      - in: query
        name: File
        description: 'Supported source file formats: doc, docx, dot, dotx, wpd, wps,
          wri'
      - in: query
        name: ImageResolutionH
        description: Image horizontal resolution (DPI)
      - in: query
        name: ImageResolutionV
        description: Image vertical resolution (DPI)
      - in: query
        name: JpgQuality
        description: Jpg image quality
      - in: query
        name: OutputFormat
        description: Supported output file formats png, jpg, tif
      - in: query
        name: StoreFile
        description: Store file on server and return url to file instead of file stream
          response
      - in: query
        name: Timeout
        description: Conversion timeout in seconds
      responses:
        200:
          description: OK
      tags:
      - Word
      - Image
  /Xps2Image:
    post:
      summary: Xps to Image
      description: The API for converting Open XML Paper Specification documents to
        PDF files. These file formats xps can be converted to png, jpg, tif.
      operationId: xps2image
      x-api-path-slug: xps2image-post
      parameters:
      - in: query
        name: ApiKey
        description: API Key should be passed if you purchased membership with credits
      - in: query
        name: File
        description: 'Supported source file formats: xps'
      - in: query
        name: ImageResolutionH
        description: Image horizontal resolution (DPI)
      - in: query
        name: ImageResolutionV
        description: Image vertical resolution (DPI)
      - in: query
        name: JpgQuality
        description: Jpg image quality
      - in: query
        name: OutputFormat
        description: Supported output file formats png, jpg, tif
      - in: query
        name: StoreFile
        description: Store file on server and return url to file instead of file stream
          response
      - in: query
        name: Timeout
        description: Conversion timeout in seconds
      responses:
        200:
          description: OK
      tags:
      - Xps
      - Image
x-streamrank:
  polling_total_time_average: 0
  polling_size_download_average: 0
  streaming_total_time_average: 0
  streaming_size_download_average: 0
  change_yes: 0
  change_no: 0
  time_percentage: 0
  size_percentage: 0
  change_percentage: 0
  last_run: ""
  days_run: 0
  minute_run: 0
---