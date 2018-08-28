{
  "info": {
    "name": "Convert API Publisher to Image",
    "_postman_id": "62525ae1-2994-4f64-b9cd-e5a214bb0b4d",
    "description": "The API for converting Publisher documents to PDF files and Images. These file formats pub can be converted to png, jpg, tif.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Email",
      "item": [
        {
          "id": "6b67b43b-d3fc-4619-a9c0-a1eb0ed857b9",
          "name": "email2image",
          "request": {
            "url": "http://do.convertapi.com/Email2Image?ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting E-Mail files to PDF files and Images. These file formats eml, mbx, msg, oft can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "a2dbcdc5-6f34-461c-a20a-ffe7c3adc231"
            }
          ]
        },
        {
          "id": "f5eeefd1-8878-4111-a298-6a593200fe18",
          "name": "email2pdf",
          "request": {
            "url": "http://do.convertapi.com/Email2Pdf?ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting E-Mail files to PDF files and Images. These file formats eml, mbx, msg, oft can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2b0934a4-a2fc-42a7-aceb-789c12c3001a"
            }
          ]
        }
      ]
    },
    {
      "name": "Excel",
      "item": [
        {
          "id": "312f6deb-13a2-4778-a1a5-a93111f17811",
          "name": "excel2image",
          "request": {
            "url": "http://do.convertapi.com/Excel2Image?AlternativeParser=%7B%7D&ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D&WorksheetActive=%7B%7D&WorksheetIndex=%7B%7D&WorksheetName=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Excel documents to PDF files and Images. These file formats csv, xls, xlsb, xlsx, xlt, xltx can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "38cfad97-dbc5-4ddf-911a-7bebe097c001"
            }
          ]
        },
        {
          "id": "81af9bce-a252-40e9-91ab-fff1bd570767",
          "name": "excel2pdf",
          "request": {
            "url": "http://do.convertapi.com/Excel2Pdf?AlternativeParser=%7B%7D&ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D&WorksheetActive=%7B%7D&WorksheetIndex=%7B%7D&WorksheetName=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Excel documents to PDF files and Images. These file formats csv, xls, xlsb, xlsx, xlt, xltx can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "03081201-8183-48c5-b5d6-7f878389f16c"
            }
          ]
        }
      ]
    },
    {
      "name": "Image",
      "item": [
        {
          "id": "c14392ef-9db8-4256-bcee-0fda6f75ec41",
          "name": "image2image",
          "request": {
            "url": "http://do.convertapi.com/Image2Image?ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Image files to PDF files and Images. These file formats avs, bmp, dcx, dib, dpx, fax, fits, fpx, gif, ico, iptc, jbig, jp2, jpeg, jpg, mdi, miff, mng, mpc, mtv, otb, pbm, pcd, pcds, pct, pcx, pgm, pict, png, pnm, ppm, psd, p7, ras, rgba, sun, tga, tiff, tif, vicar, vid, viff, wmf, xbm, xpm, xwd can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "84146d1c-af6f-4990-8b3e-435089ada7d5"
            }
          ]
        },
        {
          "id": "d4a04bae-ca65-492d-ae7b-9cd327ac38bc",
          "name": "image2pdf",
          "request": {
            "url": "http://do.convertapi.com/Image2Pdf?ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&Ocr=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Image files to PDF files and Images. These file formats avs, bmp, dcx, dib, dpx, fax, fits, fpx, gif, ico, iptc, jbig, jp2, jpeg, jpg, mdi, miff, mng, mpc, mtv, otb, pbm, pcd, pcds, pct, pcx, pgm, pict, png, pnm, ppm, psd, p7, ras, rgba, sun, tga, tiff, tif, vicar, vid, viff, wmf, xbm, xpm, xwd can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "09999e5a-9cfd-486a-b557-0a812935b104"
            }
          ]
        }
      ]
    },
    {
      "name": "Journal",
      "item": [
        {
          "id": "7f8a7285-5b22-4276-a85b-e7bb45aa309a",
          "name": "journal2image",
          "request": {
            "url": "http://do.convertapi.com/Journal2Image?ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Windows Journal Viewer documents to PDF files and Images. These file formats jnt can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cb6ccb54-7614-4d75-bba6-7587a06f0b7e"
            }
          ]
        },
        {
          "id": "ef32dfab-92e5-4a7d-8a2d-4122321f1f40",
          "name": "journal2pdf",
          "request": {
            "url": "http://do.convertapi.com/Journal2Pdf?ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Windows Journal Viewer documents to PDF files and Images. These file formats jnt can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c5106b7b-aadb-4d42-bfd7-0d8e59a1d982"
            }
          ]
        }
      ]
    },
    {
      "name": "Lotus",
      "item": [
        {
          "id": "290aa0b0-2728-4ca4-bfd8-d466e9097ae0",
          "name": "lotus2image",
          "request": {
            "url": "http://do.convertapi.com/Lotus2Image?ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Lotus Smart Suite documents to PDF files and Images. These file formats 123, 12m, wk1, wk2, wk3, lwp, mwp, sam can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "03b8ba66-4a0e-4dda-8fdf-3919a0c8bac8"
            }
          ]
        },
        {
          "id": "3b5bd6b5-59b5-429f-a8c5-904160e4279c",
          "name": "lotus2pdf",
          "request": {
            "url": "http://do.convertapi.com/Lotus2Pdf?ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Lotus Smart Suite documents to PDF files and Images. These file formats 123, 12m, wk1, wk2, wk3, lwp, mwp, sam can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "6ed50589-2752-4b70-96c1-3f6988554608"
            }
          ]
        }
      ]
    },
    {
      "name": "Open",
      "item": [
        {
          "id": "ee734af3-d4f1-462f-aa8e-84ea8a84cace",
          "name": "openoffice2image",
          "request": {
            "url": "http://do.convertapi.com/OpenOffice2Image?AlternativeParser=%7B%7D&ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting OpenOffice documents to PDF files and Images. These file formats mml, odc, odf, odg, odi, odm, odp, ods, odt, otg, oth, otp, ots, pxl, sgl, smf, srw, stc, sti, stw, sxc, sxg, sxi, sxm, sxw, vor, wv2 can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "53af4b88-9f79-4793-bc78-bcb2a39c016e"
            }
          ]
        },
        {
          "id": "f974ecf6-cdac-4e9c-93b6-4ad4b42f4db8",
          "name": "openoffice2pdf",
          "request": {
            "url": "http://do.convertapi.com/OpenOffice2Pdf?AlternativeParser=%7B%7D&ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting OpenOffice documents to PDF files and Images. These file formats mml, odc, odf, odg, odi, odm, odp, ods, odt, otg, oth, otp, ots, pxl, sgl, smf, srw, stc, sti, stw, sxc, sxg, sxi, sxm, sxw, vor, wv2 can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "23bfe6f8-aa38-4107-9c52-a70486df97a6"
            }
          ]
        }
      ]
    },
    {
      "name": "PDF",
      "item": [
        {
          "id": "e276d3a5-a795-420b-8e33-a057e4993bad",
          "name": "pdf2image",
          "request": {
            "url": "http://do.convertapi.com/Pdf2Image?ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting PDF documents to Image. These file formats pdf can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "500d4576-71c6-4756-ab36-63c8f3d8cd4f"
            }
          ]
        },
        {
          "id": "e27808d7-76c1-452d-a1bf-61f97714d91f",
          "name": "pdf2pdf",
          "request": {
            "url": "http://do.convertapi.com/Pdf2Pdf?ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting PDF documents to Image. These file formats pdf can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "90bd0822-34cb-451a-a2b6-e258ef4abd70"
            }
          ]
        },
        {
          "id": "446a1dec-9166-49b2-b8db-a0cc163369a5",
          "name": "pdf2powerpoint",
          "request": {
            "url": "http://do.convertapi.com/Pdf2PowerPoint?ApiKey=%7B%7D&File=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting PDF documents to PowerPoint presentation files. These file formats pdf, pdfa can be converted to pptx."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "e677106a-3a8a-4992-9f85-d3ff5ace7080"
            }
          ]
        }
      ]
    },
    {
      "name": "Script",
      "item": [
        {
          "id": "6c75205c-1871-4b81-a078-19cfc430a3e2",
          "name": "postscript2image",
          "request": {
            "url": "http://do.convertapi.com/PostScript2Image?ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting PostScript files to PDF files and Images. These file formats ps, eps, prn can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "b6ac77f5-417c-41bd-8860-6e50e0555067"
            }
          ]
        },
        {
          "id": "dd174209-90f5-422f-9b6d-5fd22e7c8fd9",
          "name": "postscript2pdf",
          "request": {
            "url": "http://do.convertapi.com/PostScript2Pdf?ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting PostScript files to PDF files and Images. These file formats ps, eps, prn can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "c360f63f-e0f5-421b-8136-dfe8f1144486"
            }
          ]
        }
      ]
    },
    {
      "name": "Power",
      "item": [
        {
          "id": "221c94c2-5a19-4ee8-8461-3e7022d94574",
          "name": "powerpoint2image",
          "request": {
            "url": "http://do.convertapi.com/PowerPoint2Image?AlternativeParser=%7B%7D&ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting PowerPoint documents to PDF files and Images. These file formats pot, potx, pps, ppsx, ppt, pptx can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "50547b8c-677c-498b-96de-8b50e4645143"
            }
          ]
        },
        {
          "id": "43e9883c-1311-40df-9968-91ba074bbf88",
          "name": "powerpoint2pdf",
          "request": {
            "url": "http://do.convertapi.com/PowerPoint2Pdf?AlternativeParser=%7B%7D&ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting PowerPoint documents to PDF files and Images. These file formats pot, potx, pps, ppsx, ppt, pptx can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "bb8f8a5f-1fe6-457f-9b50-347ae5da7ac6"
            }
          ]
        }
      ]
    },
    {
      "name": "Project",
      "item": [
        {
          "id": "35b2b1f2-76ff-45ad-912d-28ef4a172b29",
          "name": "project2image",
          "request": {
            "url": "http://do.convertapi.com/Project2Image?ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Project documents to PDF files and Images. These file formats mpp, mpt can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "cd685acb-e13f-4f28-9d41-6db3cf7dbaf3"
            }
          ]
        },
        {
          "id": "fb91d8e7-818e-4872-a7be-004da07aba5b",
          "name": "project2pdf",
          "request": {
            "url": "http://do.convertapi.com/Project2Pdf?ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Project documents to PDF files and Images. These file formats mpp, mpt can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "4f7cee2a-bbf3-4a3f-9a61-0e4112d24e01"
            }
          ]
        }
      ]
    },
    {
      "name": "Publisher",
      "item": [
        {
          "id": "aa8e8f63-9bc3-400b-ae9e-36d9437858ec",
          "name": "publisher2image",
          "request": {
            "url": "http://do.convertapi.com/Publisher2Image?AlternativeParser=%7B%7D&ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Publisher documents to PDF files and Images. These file formats pub can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "8ccac2d9-9220-46f2-b0e6-e873e883c21e"
            }
          ]
        }
      ]
    }
  ]
}