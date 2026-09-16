# Bảng tổng hợp giấy phép các gói phụ thuộc (pip-licenses)
| Name                   | Version     | License                                           |
|------------------------|-------------|---------------------------------------------------|
| Cython                 | 3.2.3       | Apache Software License                           |
| Django                 | 6.1.1       | BSD-3-Clause                                      |
| Flask                  | 3.1.3       | BSD-3-Clause                                      |
| ImageIO                | 2.37.2      | BSD-2-Clause                                      |
| Jinja2                 | 3.1.6       | BSD License                                       |
| MarkupSafe             | 3.0.3       | BSD-3-Clause                                      |
| PyYAML                 | 6.0.3       | MIT License                                       |
| Pygments               | 2.21.0      | BSD-2-Clause                                      |
| Werkzeug               | 3.1.8       | BSD-3-Clause                                      |
| albucore               | 0.0.24      | MIT License                                       |
| albumentations         | 2.0.8       | MIT License                                       |
| annotated-doc          | 0.0.4       | MIT                                               |
| annotated-types        | 0.7.0       | MIT License                                       |
| anyio                  | 4.12.0      | MIT                                               |
| asgiref                | 3.12.1      | BSD License                                       |
| blinker                | 1.9.0       | MIT License                                       |
| certifi                | 2025.11.12  | Mozilla Public License 2.0 (MPL 2.0)              |
| charset-normalizer     | 3.4.4       | MIT                                               |
| click                  | 8.3.1       | BSD-3-Clause                                      |
| colorama               | 0.4.6       | BSD License                                       |
| coloredlogs            | 15.0.1      | MIT License                                       |
| contourpy              | 1.3.3       | BSD License                                       |
| cycler                 | 0.12.1      | BSD License                                       |
| easydict               | 1.13        | GNU Lesser General Public License v3 (LGPLv3)     |
| fastapi                | 0.127.0     | MIT                                               |
| flatbuffers            | 25.12.19    | Apache Software License                           |
| fonttools              | 4.61.1      | MIT                                               |
| h11                    | 0.16.0      | MIT License                                       |
| humanfriendly          | 10.0        | MIT License                                       |
| idna                   | 3.11        | BSD-3-Clause                                      |
| iniconfig              | 2.3.0       | MIT                                               |
| insightface            | 0.7.3       | MIT                                               |
| itsdangerous           | 2.2.0       | BSD License                                       |
| joblib                 | 1.5.3       | BSD-3-Clause                                      |
| kiwisolver             | 1.4.9       | BSD License                                       |
| lazy_loader            | 0.4         | BSD License                                       |
| matplotlib             | 3.10.8      | Python Software Foundation License                |
| ml_dtypes              | 0.5.4       | Apache-2.0                                        |
| mpmath                 | 1.3.0       | BSD License                                       |
| networkx               | 3.6.1       | BSD-3-Clause                                      |
| numpy                  | 1.26.4      | BSD License                                       |
| onnx                   | 1.20.0      | Apache-2.0                                        |
| onnxruntime-gpu        | 1.23.2      | MIT License                                       |
| opencv-python          | 4.12.0.88   | Apache Software License                           |
| opencv-python-headless | 4.12.0.88   | Apache Software License                           |
| packaging              | 25.0        | Apache Software License; BSD License              |
| pandas                 | 3.0.5       | BSD License                                       |
| pillow                 | 12.0.0      | MIT-CMU                                           |
| pluggy                 | 1.6.0       | MIT License                                       |
| protobuf               | 6.33.2      | 3-Clause BSD License                              |
| pydantic               | 2.12.5      | MIT                                               |
| pydantic_core          | 2.41.5      | MIT                                               |
| pyodbc                 | 5.3.0       | MIT                                               |
| pyparsing              | 3.2.5       | MIT                                               |
| pyreadline3            | 3.5.4       | BSD License                                       |
| pytest                 | 9.1.1       | MIT                                               |
| python-dateutil        | 2.9.0.post0 | Apache Software License; BSD License              |
| python-multipart       | 0.0.21      | Apache-2.0                                        |
| requests               | 2.32.5      | Apache Software License                           |
| scikit-image           | 0.26.0      | BSD License                                       |
| scikit-learn           | 1.8.0       | BSD-3-Clause                                      |
| scipy                  | 1.16.3      | BSD License                                       |
| simsimd                | 6.5.12      | Apache Software License                           |
| six                    | 1.17.0      | MIT License                                       |
| sqlparse               | 0.6.0       | BSD License                                       |
| starlette              | 0.50.0      | BSD-3-Clause                                      |
| stringzilla            | 4.5.1       | Apache-2.0                                        |
| sympy                  | 1.14.0      | BSD License                                       |
| threadpoolctl          | 3.6.0       | BSD License                                       |
| tifffile               | 2025.12.20  | BSD-3-Clause                                      |
| tqdm                   | 4.67.1      | MIT License; Mozilla Public License 2.0 (MPL 2.0) |
| typing-inspection      | 0.4.2       | MIT                                               |
| typing_extensions      | 4.15.0      | PSF-2.0                                           |
| tzdata                 | 2026.4      | Apache-2.0                                        |
| urllib3                | 2.6.2       | MIT                                               |
| uvicorn                | 0.40.0      | BSD-3-Clause                                      |
## Phân tích nghĩa vụ tuân thủ
Kiểm tra nhóm Copyleft mạnh:** Danh sách trên chủ yếu chứa các gói có giấy phép Dễ dãi (Permissive) như MIT, BSD, Apache-2.0, PSF. Không xuất hiện gói thuộc nhóm Copyleft mạnh (GNU GPL).
Nghĩa vụ phát sinh nếu đóng mã thương mại:**
Các gói MIT / BSD / Apache 2.0 cho phép đóng mã nguồn thương mại, chỉ cần giữ lại thông báo bản quyền (Copyright Notice) và nội dung giấy phép gốc trong phần thông tin phần mềm.
Nếu xuất hiện gói GPL (Copyleft mạnh), dự án bắt buộc phải mở toàn bộ mã nguồn. Do đó cần loại bỏ hoặc thay thế gói GPL bằng thư viện khác có giấy phép dễ dãi hơn.
