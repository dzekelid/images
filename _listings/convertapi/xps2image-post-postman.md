{
  "info": {
    "name": "Convert API Xps to Image",
    "_postman_id": "63848a06-ea8b-4fd8-ae7b-59f256cab31d",
    "description": "The API for converting Open XML Paper Specification documents to PDF files. These file formats xps can be converted to png, jpg, tif.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Email",
      "item": [
        {
          "id": "fcf204a5-4624-4a58-b60a-f4a52c208c0c",
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
              "id": "bfb08af5-5a62-4f2d-986d-5007ea676528"
            }
          ]
        },
        {
          "id": "22799fd6-6b84-4c8c-b183-7e35bbf20c72",
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
              "id": "6271be39-22c8-43af-8923-4aec04c7b3ac"
            }
          ]
        }
      ]
    },
    {
      "name": "Excel",
      "item": [
        {
          "id": "c9634490-9a8b-4241-9c6e-32e52990e641",
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
              "id": "b96c3e4b-e15c-4dec-af6f-8ff6fee511a5"
            }
          ]
        },
        {
          "id": "b95979a6-6731-45ed-82d8-c8b9e6db81aa",
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
              "id": "fd9e88ce-d113-4e25-8fcc-09d56c4e3463"
            }
          ]
        }
      ]
    },
    {
      "name": "Image",
      "item": [
        {
          "id": "ee1676e8-7bfc-4796-af28-65e751454096",
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
              "id": "152380ba-5466-4cd8-8ebf-81981e90572b"
            }
          ]
        },
        {
          "id": "d8175d75-6b36-4260-903d-029c56d1f287",
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
              "id": "db2dc192-30b4-4256-b83d-b7d1666f2a73"
            }
          ]
        }
      ]
    },
    {
      "name": "Journal",
      "item": [
        {
          "id": "c2bb6cf3-0c8d-4548-97f8-e4bc8779ebf7",
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
              "id": "29e218d3-669b-4ab0-a5c7-8c41d9653b52"
            }
          ]
        },
        {
          "id": "341c3bd8-daaa-405f-9f4b-f6a5fd6e3253",
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
              "id": "173f34a7-d9c3-4108-b4b2-326565fb8820"
            }
          ]
        }
      ]
    },
    {
      "name": "Lotus",
      "item": [
        {
          "id": "2d1f1ee5-02e9-4730-b8eb-9c5c3f92a4e1",
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
              "id": "7019902b-cd82-4e2a-ab2b-58d8c7c0bc6d"
            }
          ]
        },
        {
          "id": "5b24e480-0bf5-4cb1-8c98-db0d70a0f45d",
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
              "id": "0f44f5ca-becf-45a3-9d82-c2ea8a02e29d"
            }
          ]
        }
      ]
    },
    {
      "name": "Open",
      "item": [
        {
          "id": "c84f60ce-86c2-4d6a-912b-820f7a0a15d1",
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
              "id": "a636c959-533b-498c-a49a-02c03f1643a5"
            }
          ]
        },
        {
          "id": "0e50f94f-3c6a-43b3-82e1-66d79c0e79cf",
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
              "id": "4afcfc2a-d8e3-407b-8966-a5191800b0bd"
            }
          ]
        }
      ]
    },
    {
      "name": "PDF",
      "item": [
        {
          "id": "4639e17e-2d84-41c8-b610-4a6262506437",
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
              "id": "3facf7e7-a89d-4972-8913-bdb3921af6ad"
            }
          ]
        },
        {
          "id": "0bcbfc66-32f7-41f8-93db-07ec27078e6a",
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
              "id": "0b2dba36-bd62-48e6-9972-3480cf99dd3f"
            }
          ]
        },
        {
          "id": "0ddb7522-bdb8-4ca6-9d0f-96c53206cbf5",
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
              "id": "edc67650-23c0-4b64-b0e9-9c7363aa4042"
            }
          ]
        }
      ]
    },
    {
      "name": "Script",
      "item": [
        {
          "id": "4d780c01-1282-4201-877a-205161174512",
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
              "id": "11f48961-28a7-4748-b0c1-d4fc7e733c45"
            }
          ]
        },
        {
          "id": "718b94a0-156a-4397-8cd9-a133c804d23d",
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
              "id": "a3b5e2f1-d9fd-4c72-9635-b420a68773a8"
            }
          ]
        }
      ]
    },
    {
      "name": "Power",
      "item": [
        {
          "id": "c7242501-6eb8-4ee8-ba3e-4774c2d2e654",
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
              "id": "a941ea0f-637a-4751-a49e-98732c1a5c19"
            }
          ]
        },
        {
          "id": "51d6ab8a-87b4-499b-82d5-e91fd0150788",
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
              "id": "db20e3ed-076d-47fb-aa19-4d97465126c8"
            }
          ]
        }
      ]
    },
    {
      "name": "Project",
      "item": [
        {
          "id": "0896d149-63ce-4dd8-99d7-6022c7da2726",
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
              "id": "7dc9ea12-a955-4acf-ae43-48ed9ab97477"
            }
          ]
        },
        {
          "id": "a85f2083-d9f1-40b5-9266-c7be3ad913fd",
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
              "id": "8a129340-2012-482d-b91a-baaddee52bcf"
            }
          ]
        }
      ]
    },
    {
      "name": "Publisher",
      "item": [
        {
          "id": "2d14655e-45c7-4c3d-bf5d-8d3c4df6f4af",
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
              "id": "4362b790-37eb-40de-8092-2b88c3edadbc"
            }
          ]
        },
        {
          "id": "5ac9a816-0e66-45ce-b4ee-384f21888943",
          "name": "publisher2pdf",
          "request": {
            "url": "http://do.convertapi.com/Publisher2Pdf?AlternativeParser=%7B%7D&ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Publisher documents to PDF files and Images. These file formats pub can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "3b23e692-c6e4-49a9-b94f-72420254a100"
            }
          ]
        }
      ]
    },
    {
      "name": "Rich",
      "item": [
        {
          "id": "83559ca4-ac70-4019-9513-27df99d9ecba",
          "name": "richtext2image",
          "request": {
            "url": "http://do.convertapi.com/RichText2Image?ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Rich Text documents to PDF files and Images. These file formats rtf can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "47909347-8c74-488b-9a8b-d62a0894e72d"
            }
          ]
        },
        {
          "id": "f081e62a-276e-4370-91da-3851ddfdbf0c",
          "name": "richtext2pdf",
          "request": {
            "url": "http://do.convertapi.com/RichText2Pdf?ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Rich Text documents to PDF files and Images. These file formats rtf can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f236b8bc-874d-4ee0-8fea-ac1e84e5eb59"
            }
          ]
        }
      ]
    },
    {
      "name": "Snap",
      "item": [
        {
          "id": "d6ba87f4-9aad-4be1-b7fd-6233c5e62f93",
          "name": "snapshot2image",
          "request": {
            "url": "http://do.convertapi.com/SnapShot2Image?ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Access Report Snapshots documents to PDF files and Images. These file formats snp can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2f699761-f91e-454a-bedb-f16377298c67"
            }
          ]
        },
        {
          "id": "68f16838-508e-412b-86f5-44799aa67ee3",
          "name": "snapshot2pdf",
          "request": {
            "url": "http://do.convertapi.com/SnapShot2Pdf?ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Access Report Snapshots documents to PDF files and Images. These file formats snp can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "9339aca4-2a13-4bbc-9328-7101c90d8e45"
            }
          ]
        }
      ]
    },
    {
      "name": "Text",
      "item": [
        {
          "id": "9a0a1c6c-adab-41ed-b4dd-e1b014cd5bac",
          "name": "text2image",
          "request": {
            "url": "http://do.convertapi.com/Text2Image?ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Textual files to PDF files and Images. These file formats txt, log can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "041914c0-35be-4069-af3b-5916dcc2dbd7"
            }
          ]
        },
        {
          "id": "56f1d22b-ebf7-4ba4-b996-e180e685a818",
          "name": "text2pdf",
          "request": {
            "url": "http://do.convertapi.com/Text2Pdf?ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Textual files to PDF files and Images. These file formats txt, log can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "31ab5814-e037-443f-b6fa-2839e86f6504"
            }
          ]
        }
      ]
    },
    {
      "name": "Visio",
      "item": [
        {
          "id": "5bd06866-2342-4306-afcc-57795ade118a",
          "name": "visio2image",
          "request": {
            "url": "http://do.convertapi.com/Visio2Image?AlternativeParser=%7B%7D&ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Visio documents to PDF files and Images. These file formats vsd, vst, vsdx, vstx can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "f2f35c21-40df-4b04-8d3a-a9b968cbdf58"
            }
          ]
        },
        {
          "id": "4c4bce5c-c317-4576-ab4f-bbcdb040e3ac",
          "name": "visio2pdf",
          "request": {
            "url": "http://do.convertapi.com/Visio2Pdf?AlternativeParser=%7B%7D&ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Visio documents to PDF files and Images. These file formats vsd, vst, vsdx, vstx can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "58850de1-7513-4d28-a22b-c0784d9766e0"
            }
          ]
        }
      ]
    },
    {
      "name": "Web",
      "item": [
        {
          "id": "78255b31-eb1c-4adc-8e8f-b9dc625636e4",
          "name": "web2image",
          "request": {
            "url": "http://do.convertapi.com/Web2Image?AcceptLanguage=%7B%7D&AlternativeParser=%7B%7D&ApiKey=%7B%7D&AuthPassword=%7B%7D&AuthUsername=%7B%7D&ConversionDelay=%7B%7D&CUrl=%7B%7D&PageHeight=%7B%7D&PageWidth=%7B%7D&Plugins=%7B%7D&Scripts=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D&UserAgent=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Web Pages to Images."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "aa444207-88de-4743-b63d-4b4bb885be8f"
            }
          ]
        },
        {
          "id": "746acaa5-2174-452b-a8fa-412e733ad95d",
          "name": "web2pdf",
          "request": {
            "url": "http://do.convertapi.com/Web2Pdf?AcceptLanguage=%7B%7D&AlternativeParser=%7B%7D&ApiKey=%7B%7D&AuthPassword=%7B%7D&AuthUsername=%7B%7D&Background=%7B%7D&ConversionDelay=%7B%7D&CoverUrl=%7B%7D&CUrl=%7B%7D&DocumentTitle=%7B%7D&FooterLine=%7B%7D&FooterSpacing=%7B%7D&FooterTextCenter=%7B%7D&FooterTextFont=%7B%7D&FooterTextLeft=%7B%7D&FooterTextRight=%7B%7D&FooterTextSize=%7B%7D&FooterUrl=%7B%7D&HeaderLine=%7B%7D&HeaderSpacing=%7B%7D&HeaderTextCenter=%7B%7D&HeaderTextFont=%7B%7D&HeaderTextLeft=%7B%7D&HeaderTextRight=%7B%7D&HeaderTextSize=%7B%7D&HeaderUrl=%7B%7D&InfoStamp=%7B%7D&LowQuality=%7B%7D&MarginBottom=%7B%7D&MarginLeft=%7B%7D&MarginRight=%7B%7D&MarginTop=%7B%7D&Outline=%7B%7D&PageHeight=%7B%7D&PageNo=%7B%7D&PageOrientation=%7B%7D&PageSize=%7B%7D&PageWidth=%7B%7D&Plugins=%7B%7D&PrintType=%7B%7D&Scripts=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D&UserAgent=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Web Pages to PDF files."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "2d2c56f1-2fe3-4bf7-bbee-aaecef6472dd"
            }
          ]
        }
      ]
    },
    {
      "name": "Word",
      "item": [
        {
          "id": "934fe79b-04e1-445b-ab84-95d818b193b7",
          "name": "word2image",
          "request": {
            "url": "http://do.convertapi.com/Word2Image?AlternativeParser=%7B%7D&ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Word documents to PDF files and Images. These file formats doc, docx, dot, dotx, wpd, wps, wri can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "5785994d-ed2d-4eaf-8ee3-0af81c3372a1"
            }
          ]
        },
        {
          "id": "ba5d6d9e-394d-4236-9f84-e423f9d871df",
          "name": "word2pdf",
          "request": {
            "url": "http://do.convertapi.com/Word2Pdf?AlternativeParser=%7B%7D&ApiKey=%7B%7D&DocumentAuthor=%7B%7D&DocumentKeywords=%7B%7D&DocumentSubject=%7B%7D&DocumentTitle=%7B%7D&File=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Word documents to PDF files and Images. These file formats doc, docx, dot, dotx, wpd, wps, wri can be converted to pdf, pdfa, png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "225ec605-d3c8-43b0-bc17-418c3788c630"
            }
          ]
        }
      ]
    },
    {
      "name": "Xps",
      "item": [
        {
          "id": "3afd49eb-9dc4-47d7-91f3-2b3d012454e9",
          "name": "xps2image",
          "request": {
            "url": "http://do.convertapi.com/Xps2Image?ApiKey=%7B%7D&File=%7B%7D&ImageResolutionH=%7B%7D&ImageResolutionV=%7B%7D&JpgQuality=%7B%7D&OutputFormat=%7B%7D&StoreFile=%7B%7D&Timeout=%7B%7D",
            "method": "POST",
            "body": {
              "mode": "raw"
            },
            "description": "The API for converting Open XML Paper Specification documents to PDF files. These file formats xps can be converted to png, jpg, tif."
          },
          "response": [
            {
              "status": "OK",
              "code": 200,
              "name": "Response_200",
              "id": "87d4981c-22ed-41b2-b13d-338d95ae0766"
            }
          ]
        }
      ]
    }
  ]
}