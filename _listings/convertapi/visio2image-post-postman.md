{
  "info": {
    "name": "Convert API Visio to Image",
    "_postman_id": "d95f3df9-ec33-4773-ae4d-e4de68582bfa",
    "description": "The API for converting Visio documents to PDF files and Images. These file formats vsd, vst, vsdx, vstx can be converted to png, jpg, tif.",
    "schema": "https://schema.getpostman.com/json/collection/v2.0.0/"
  },
  "item": [
    {
      "name": "Email",
      "item": [
        {
          "id": "14b1ee33-19e7-470b-a3f6-57b400640366",
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
              "id": "8c9130eb-f539-4e53-93d2-435181058b03"
            }
          ]
        },
        {
          "id": "05f874d8-4076-4542-943c-8f28aeaf370d",
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
              "id": "70c984c9-72f3-456a-82ce-7099fb7b2a9c"
            }
          ]
        }
      ]
    },
    {
      "name": "Excel",
      "item": [
        {
          "id": "9f2b3bcb-0f66-401a-a09c-7991be26eaa5",
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
              "id": "230d35f4-6337-40a2-b523-dd56083a24d0"
            }
          ]
        },
        {
          "id": "150f60a3-12c7-452f-bc8a-3c72afb8a451",
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
              "id": "08f64c93-2f2f-4c47-a5ba-481ec68026c2"
            }
          ]
        }
      ]
    },
    {
      "name": "Image",
      "item": [
        {
          "id": "e9850bc7-df27-4775-adab-809b901e7da4",
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
              "id": "cc24f72b-894a-48ec-875c-7864adfa3afc"
            }
          ]
        },
        {
          "id": "0f0d6dc2-6551-4d0c-8d28-51e71d10577b",
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
              "id": "b50f6a6f-baa9-45f3-b00b-c6e0525ef89a"
            }
          ]
        }
      ]
    },
    {
      "name": "Journal",
      "item": [
        {
          "id": "f83eea48-69c7-484c-885b-9893849f5c0a",
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
              "id": "f803cbcb-34c9-497d-a204-0c87a4ff7049"
            }
          ]
        },
        {
          "id": "5ee9a3f0-9569-45cb-aa68-4e743903615b",
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
              "id": "9399d8d0-f41e-4bdf-9136-b1614d4efea4"
            }
          ]
        }
      ]
    },
    {
      "name": "Lotus",
      "item": [
        {
          "id": "d1256474-1237-45b5-bc93-a6beeff90c68",
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
              "id": "889a0be3-d8fe-4ba4-8a18-b394daf4f165"
            }
          ]
        },
        {
          "id": "a2942eb7-5b2e-42db-a879-95c4c8e2f326",
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
              "id": "772e5d92-5297-4d4b-b3e7-0299832a8dc9"
            }
          ]
        }
      ]
    },
    {
      "name": "Open",
      "item": [
        {
          "id": "c78d8a00-8488-4964-b206-442e765d4435",
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
              "id": "ba4e3ba1-d4e1-4a02-9307-45182fdb5518"
            }
          ]
        },
        {
          "id": "c52b6c66-7487-48d1-84bb-6fdb71f01921",
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
              "id": "57324f62-f2bf-4627-972f-70c8839be878"
            }
          ]
        }
      ]
    },
    {
      "name": "PDF",
      "item": [
        {
          "id": "684116e3-a390-4acf-aba6-b08a50017828",
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
              "id": "0836751c-12ef-432b-8093-20c8104c54f1"
            }
          ]
        },
        {
          "id": "0b0aecfa-fc23-4118-8077-4b2d9a5047ce",
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
              "id": "0924f3c1-7c8c-4655-a9e1-127ed83177f0"
            }
          ]
        },
        {
          "id": "1cd06070-19e2-4f46-9254-60407c1595a3",
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
              "id": "44bbbb66-d3a6-425f-8e96-6ded408dfe2a"
            }
          ]
        }
      ]
    },
    {
      "name": "Script",
      "item": [
        {
          "id": "74e5737b-bf2d-483d-926d-efcd89e9715c",
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
              "id": "5ea2a79f-f541-4f85-a5b1-bb7fbe4774e1"
            }
          ]
        },
        {
          "id": "be607050-b9a6-4eb2-ac76-1e2928da4303",
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
              "id": "ab1829c2-a95a-43a0-b462-b3b0d84700d1"
            }
          ]
        }
      ]
    },
    {
      "name": "Power",
      "item": [
        {
          "id": "bfe80219-d05b-4ed1-8cfa-c2dc47ec92fc",
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
              "id": "59e8e392-009a-4ab5-bbf3-6dd269f33dab"
            }
          ]
        },
        {
          "id": "67e036c8-63c6-4bf8-ac5c-d94d9808cde0",
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
              "id": "b59319bc-0b80-4158-bb9d-1e2be3e5fa41"
            }
          ]
        }
      ]
    },
    {
      "name": "Project",
      "item": [
        {
          "id": "a9338648-e5f3-48ef-b7cd-124a5c9ecced",
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
              "id": "cc253485-13e8-4f40-81f3-6e26215028c6"
            }
          ]
        },
        {
          "id": "4d042d9d-e0b8-48f2-8325-a9595d3caa45",
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
              "id": "32145d0d-eaee-471d-860b-4d36c74f60e0"
            }
          ]
        }
      ]
    },
    {
      "name": "Publisher",
      "item": [
        {
          "id": "1d709b72-4be2-478a-b1bc-41927e21a13b",
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
              "id": "41b55445-7431-4b8d-95a2-a7f260a906f7"
            }
          ]
        },
        {
          "id": "3f0250cb-4bde-4af6-abb1-9f97f84f9500",
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
              "id": "96734fe6-c26d-4a7a-82ae-16aa29cce529"
            }
          ]
        }
      ]
    },
    {
      "name": "Rich",
      "item": [
        {
          "id": "822ddaeb-9da6-4d93-a988-25d2bdd267ec",
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
              "id": "0882e406-bf08-4a0e-959b-ec03af762de6"
            }
          ]
        },
        {
          "id": "455d806d-b7f1-4e0c-a03a-2af5f384c611",
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
              "id": "b1bcd005-7c35-4c66-b021-274e7c8865a4"
            }
          ]
        }
      ]
    },
    {
      "name": "Snap",
      "item": [
        {
          "id": "5767e4a3-1f92-427f-8bf8-7eca77ad1344",
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
              "id": "55a55ac4-51d9-488d-8cc3-5f2fea754d5c"
            }
          ]
        },
        {
          "id": "12f1ac48-54b7-4dc3-af7f-c9cba6f5aa64",
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
              "id": "a4cb4a87-e5a3-4622-af32-f2e1cef547b0"
            }
          ]
        }
      ]
    },
    {
      "name": "Text",
      "item": [
        {
          "id": "3069e120-6406-4750-ad02-a0ab7375e2b4",
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
              "id": "27e944e7-6ef9-4cbe-b6c5-059f4d5bb053"
            }
          ]
        },
        {
          "id": "658f496f-8925-40ef-bf54-65e11a3f439b",
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
              "id": "fa28c81b-34c2-40f7-8ff2-59057f22046a"
            }
          ]
        }
      ]
    },
    {
      "name": "Visio",
      "item": [
        {
          "id": "00802eda-bf71-49e9-9df4-6825a08c1eb7",
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
              "id": "438583e8-0b25-4d20-9676-e9d57776f8f3"
            }
          ]
        }
      ]
    }
  ]
}