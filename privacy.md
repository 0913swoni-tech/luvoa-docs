privacy_ko.html



LUVOA 개인정보 처리방침

최종 수정일: 2026년 6월 28일

개요
Prime Node("회사", "당사")는 LUVOA 애플리케이션을 운영합니다. 당사는 이용자의 개인정보 보호를 최우선 가치로 여깁니다. 본 개인정보 처리방침은 당사가 취급하는 정보에 대한 엄격한 처리 기준을 설명합니다.

로컬 우선(Local-First) 하이브리드 아키텍처 및 무로그(Zero-Log) 정책
LUVOA는 완전한 온디바이스(On-device) 원칙과 제로 로그 기술을 기반으로 정교하게 설계되었습니다.
- 완벽한 데이터 격리: 개인 설정, 즐겨찾기 명언, 이용 기록 등은 전적으로 이용자의 로컬 기기에만 안전하게 저장됩니다.
- 서버 내 데이터 미저장: 당사는 이용자의 개인 이용 데이터, 열람 기록, 즐겨찾기 명언을 당사 서버로 전송, 수집 또는 저장하지 않습니다. 이용자는 자신의 데이터에 대한 완전한 소유권과 통제권을 가집니다.
- 데이터 삭제 및 이용자의 책임: 철저한 개인정보 보호를 위해 데이터가 기기 내에만 저장되므로, LUVOA 앱을 삭제하면 저장된 모든 데이터가 영구적이고 복구 불가능하게 삭제됩니다. 당사는 어떠한 서버에도 백업 사본을 보관하지 않으며, 기기 변경, 분실, 파손 또는 앱 삭제로 인해 손실된 데이터를 복구할 수 없습니다. 기기 백업 관리는 전적으로 이용자 본인의 책임입니다.

서비스 안정성을 위한 최소한의 데이터 수집
원활한 서비스 환경 제공 및 앱 안정성 확보를 위해, 식별 불가능하도록 철저히 익명화된 비개인 식별 데이터에 한해 수집될 수 있습니다.
- 이용 데이터: 앱 안정성 개선 목적으로만 엄격히 사용되는 익명 진단 데이터(예: 충돌 로그)

제3자 서비스 제공자 (엄격히 제한된 범위)
VVIP 멤버십 기능 제공 및 핵심 인프라 유지를 위해, 엄격한 비밀유지 계약이 적용된 신뢰할 수 있는 제3자 서비스를 활용합니다.
- Apple App Store 및 Google Play 서비스: 앱 배포 및 기본 시스템 서비스 연동
- RevenueCat: 인앱 결제의 안전한 처리 및 프리미엄 구독 관리에만 전적으로 사용됩니다. 당사는 이용자의 신용카드 번호나 금융 정보를 직접 수집, 처리 또는 저장하지 않습니다.
- Firebase (Google): FCM 서버리스 푸시(사일런트 메시지)는 텍스트 본문 없는 가벼운 신호만을 전송하여 백그라운드 상태의 앱을 깨우는 데만 엄격히 활용되며, 이를 통해 로컬 데이터와 연동된 0ms 즉각 오프라인 렌더링을 구현합니다. 이 과정에서 어떠한 개인 식별 정보도 수집되거나 전송되지 않습니다.
- Supabase: 스토어 업데이트 없이 앱 콘텐츠(명언, 배경 이미지, 아이콘)를 실시간 반영(OTA 배포)하기 위한 '읽기 전용' 백엔드 인프라로만 엄격히 사용됩니다. 이용자의 개인 데이터(즐겨찾기, 책갈피, 확언 등)는 Supabase 서버로 절대 전송되거나 저장되지 않습니다. 데이터 유출을 완벽히 방지하기 위해 당사 인프라에는 행 단위 보안(RLS, Row Level Security)이 철저히 적용되어 있습니다.

아동의 개인정보 보호
LUVOA는 성인 이용자를 위해 고안된 전문 애플리케이션입니다. 당사는 만 14세 미만 아동의 서비스 이용을 엄격히 제한합니다. 당사는 만 14세 미만 아동의 개인 식별 정보를 고의로 수집하지 않습니다. 만약 해당 정보가 수집된 사실을 인지하게 될 경우, 시스템에서 즉시 영구 삭제 조치합니다.

데이터 보안
당사는 인프라에서 처리되는 익명 데이터를 보호하기 위해 행 단위 보안(RLS) 및 암호화를 포함한 업계 표준 보안 조치를 적용하고 있습니다. 다만, 전자적 저장 방식이나 인터넷 전송 방식 중 100% 완벽하게 안전한 방법은 존재하지 않으므로 절대적인 보안을 완전히 보장할 수는 없습니다.

방침의 변경 및 문의
당사는 언제든지 본 개인정보 처리방침을 개정할 권리를 보유합니다. 변경 사항은 본 페이지 상단의 "최종 수정일"을 업데이트하여 공지합니다. 개인정보 보호와 관련된 모든 문의 사항은 개인정보 보호책임자(primenode.corp@gmail.com)에게 접수해 주시기 바랍니다.


privacy_en.html



LUVOA Privacy Policy
Last Updated: June 28, 2026

Introduction Prime Node ("Company", "we", "us") operates the LUVOA application. We consider privacy our highest priority. This Privacy Policy explains our strict guidelines regarding the information we handle.

Local-First Hybrid Architecture & Zero-Log Policy LUVOA is meticulously engineered on a complete on-device principle and zero-log technology.

Absolute Data Isolation: Personal settings, favorite quotes, and usage history are stored entirely and exclusively on your local device.

No Data Storage on Servers: We DO NOT transmit, collect, or store your personal usage data, reading history, or favorite quotes on our servers. You retain complete ownership and control over your data.

Data Deletion & User Responsibility: Because your data is stored locally for maximum privacy, deleting the LUVOA app will permanently and irretrievably erase all stored data. We do not keep backup copies on any server, and we cannot recover data lost due to device upgrades, loss, damage, or app deletion. Managing device backups is solely the user's responsibility.

Limited Data Collection for Service Stability To provide a seamless experience and ensure app stability, we may collect strictly anonymized, non-personally identifiable data:
Usage Data: Anonymous diagnostic data (e.g., crash logs) strictly used for improving app stability.

Third-Party Services (Strictly Limited Scope) To provide VVIP membership features and maintain core infrastructure, we use trusted third-party services bound by strict confidentiality agreements.
Apple App Store & Google Play Services: For app distribution and foundational services.

RevenueCat: Used exclusively to process in-app purchases securely and manage premium subscriptions. We do not collect, process, or store your credit card or financial information.

Firebase (Google): FCM Serverless Push (Silent Message) is strictly utilized to send light empty signals (without heavy text content) to wake the app in the background, enabling 0ms offline rendering matched with local data. No personally identifiable information is collected or transmitted during this process.

Supabase: Used strictly as a 'read-only' backend infrastructure to deploy Over-The-Air (OTA) updates for app content (quotes, background images, icons) without requiring a store update. Your personal data (favorites, bookmarks, affirmations) is NEVER transmitted to or stored on Supabase servers. To completely prevent data theft, Row Level Security (RLS) is strictly applied to our infrastructure.

Children's Privacy LUVOA is an advanced application designed for adult users. We strictly restrict our services from users under the age of 14. We do not knowingly collect personally identifiable information from anyone under 14. If we become aware that such information has been provided, we will immediately and permanently delete it from our systems.

Data Security We use commercially acceptable, industry-standard security measures, including Row Level Security (RLS) and encryption, to protect any anonymized data handled by our infrastructure. However, no method of electronic storage or transmission over the internet is 100% secure, and we cannot guarantee absolute security.

Changes & Contact We reserve the right to update this Privacy Policy at any time. Changes will be posted on this page with an updated "Last Updated" date. For any privacy-related inquiries, please contact our Privacy Officer at primenode.corp@gmail.com.


privacy_ja.html



LUVOA プライバシーポリシー

最終改定日: 2026年6月28日

はじめに
Prime Node（以下「当社」）は、LUVOAアプリケーションを運営しています。当社はお客様のプライバシーを最優先事項として考えております。本プライバシーポリシーでは、当社が取り扱う情報に関する厳格なガイドラインについて説明します。

ローカルファースト・ハイブリッドアーキテクチャおよびゼロログポリシー
LUVOAは、完全なオンデバイス（端末内完結）の原則とゼロログ技術に基づいて精巧に構築されています。
- 完全なデータ隔離: 個人設定、お気に入りの名言、利用履歴は、すべてお客様の端末内にのみ安全に保存されます。
- サーバーへのデータ非保存: 当社は、お客様の個人利用データ、閲覧履歴、お気に入りの名言を当社サーバーへ送信、収集、または保存することは一切ありません。お客様はご自身のデータに対して完全な所有権と制御権を有します。
- データ削除とユーザーの責任: 徹底したプライバシー保護のためデータは端末内にのみ保存されるため、LUVOAアプリを削除すると、保存されたすべてのデータが永久的かつ復元不可能な形で消去されます。当社はいかなるサーバーにもバックアップのコピーを保持しておらず、端末の変更、紛失、破損、またはアプリの削除によって失われたデータを復元することはできません。端末のバックアップ管理は、完全にユーザー自身の責任となります。

サービス安定性のための最小限のデータ収集
快適な利用環境の提供およびアプリの安定性確保のため、個人を特定できない完全に匿名化された非個人情報に限り収集される場合があります。
- 利用データ: アプリの安定性向上の目的にのみ厳格に使用される匿名の診断データ（例: クラッシュログ）

サードパーティサービス（厳格に制限された範囲）
VVIPメンバーシップ機能の提供およびコアインフラの維持のため、厳格な秘密保持契約を締結した信頼できるサードパーティサービスを利用しています。
- Apple App Store & Google Play サービス: アプリの配信および基盤システムの連携
- RevenueCat: アプリ内課金の安全な処理およびプレミアム定期購入の管理にのみ独占的に使用されます。当社はお客様のクレジットカード番号や金融情報を直接収集、処理、または保存しません。
- Firebase (Google): FCMサーバーレスプッシュ（サイレントメッセージ）は、テキスト本文を含まない軽量なシグナルのみを送信してバックグラウンドのアプリを起動するために厳格に利用され、ローカルデータと連動した0msの即時オフラインレンダリングを実現します。このプロセス中に個人を特定できる情報が収集または送信されることはありません。
- Supabase: ストアでのアプリアップデートを必要とせずに、コンテンツ（名言、背景画像、アイコン）をリアルタイム配信（OTA配信）するための「読み取り専用」バックエンドインフラとしてのみ厳格に使用されます。お客様の個人データ（お気に入り、ブックマーク、アファメーション等）がSupabaseサーバーに送信または保存されることは絶対にありません。データの不正アクセスを完全に防ぐため、当社のインフラには行レベルセキュリティ（RLS）が徹底して適用されています。

子どものプライバシー
LUVOAは成人ユーザー向けに設計された高度なアプリケーションです。当社は14歳未満のユーザーによる本サービスの利用を厳格に制限しています。当社は14歳未満の者から個人を特定できる情報を意図的に収集することはありません。万が一、そのような情報が提供されたことを認識した場合、システムから直ちに永久削除いたします。

データセキュリティ
当社は、インフラストラクチャによって取り扱われる匿名化されたデータを保護するため、行レベルセキュリティ（RLS）や暗号化を含む業界標準のセキュリティ対策を実施しています。ただし、電子的な保存方法やインターネット上の送信方法において100%安全なものは存在しないため、絶対的なセキュリティを完全に保証することはできません。

改定およびお問い合わせ
当社は、本プライバシーポリシーをいつでも更新する権利を留保します。変更内容は、本ページ上部の「最終改定日」を更新して掲載されます。プライバシーに関するお問い合わせは、当社の個人情報保護担当（primenode.corp@gmail.com）までご連絡ください。


privacy_es.html



Política de privacidad de LUVOA

Última actualización: 28 de junio de 2026

Introducción
Prime Node ("Empresa", "nosotros", "nos") opera la aplicación LUVOA. Consideramos la privacidad nuestra máxima prioridad. Esta Política de privacidad explica nuestras directrices estrictas con respecto a la información que gestionamos.

Arquitectura híbrida de procesamiento local prioritario y política de cero registros (Zero-Log)
LUVOA está meticulosamente diseñada bajo un principio de funcionamiento integral en el dispositivo y tecnología de cero registros.
- Aislamiento absoluto de datos: Los ajustes personales, las frases favoritas y el historial de uso se almacenan de manera total y exclusiva en tu dispositivo local.
- Sin almacenamiento de datos en servidores: NO transmitimos, recopilamos ni almacenamos tus datos de uso personal, historial de lectura o frases favoritas en nuestros servidores. Conservas la propiedad y el control absolutos sobre tus datos.
- Eliminación de datos y responsabilidad del usuario: Dado que tus datos se almacenan localmente para garantizar la máxima privacidad, desinstalar la aplicación LUVOA borrará de forma permanente e irrecuperable todos los datos almacenados. No guardamos copias de seguridad en ningún servidor y no podemos recuperar los datos perdidos por cambio de dispositivo, pérdida, daño o desinstalación de la app. La gestión de las copias de seguridad del dispositivo es responsabilidad exclusiva del usuario.

Recopilación limitada de datos para la estabilidad del servicio
Para proporcionar una experiencia óptima y garantizar la estabilidad de la aplicación, podemos recopilar datos estrictamente anónimos y no identificables personalmente:
- Datos de uso: Datos de diagnóstico anónimos (por ejemplo, registros de errores y fallos) utilizados estrictamente para mejorar la estabilidad de la aplicación.

Servicios de terceros (alcance estrictamente limitado)
Para ofrecer las funciones de membresía VVIP y mantener la infraestructura principal, utilizamos servicios de terceros de confianza sujetos a estrictos acuerdos de confidencialidad.
- Apple App Store y Google Play Services: Para la distribución de la aplicación y servicios del sistema base.
- RevenueCat: Se utiliza exclusivamente para procesar compras dentro de la aplicación de forma segura y gestionar suscripciones premium. No recopilamos, procesamos ni almacenamos la información de tu tarjeta de crédito ni tus datos financieros.
- Firebase (Google): El servicio de notificaciones push sin servidor FCM (Silent Message) se utiliza estrictamente para enviar señales ligeras sin contenido de texto para activar la aplicación en segundo plano, lo que permite un renderizado local instantáneo de 0 ms. No se recopila ni transmite ninguna información de identificación personal durante este proceso.
- Supabase: Se utiliza estrictamente como una infraestructura backend de "solo lectura" para desplegar actualizaciones de contenido en tiempo real (OTA) (frases, imágenes de fondo, iconos) sin necesidad de una actualización en la tienda. Tus datos personales (favoritos, marcadores, afirmaciones) NUNCA se transmiten ni se almacenan en los servidores de Supabase. Para prevenir por completo la filtración de datos, se aplica estrictamente la seguridad a nivel de fila (RLS, Row Level Security) en nuestra infraestructura.

Privacidad de los menores
LUVOA es una aplicación avanzada diseñada para usuarios adultos. Restringimos estrictamente nuestros servicios a menores de 14 años. No recopilamos a sabiendas información de identificación personal de menores de 14 años. Si detectamos que se nos ha proporcionado dicha información, la eliminaremos de inmediato y de forma permanente de nuestros sistemas.

Seguridad de los datos
Utilizamos medidas de seguridad estándar de la industria y comercialmente aceptables, incluidas la seguridad a nivel de fila (RLS) y el cifrado, para proteger cualquier dato anónimo gestionado por nuestra infraestructura. Sin embargo, ningún método de almacenamiento electrónico o transmisión por internet es 100% seguro, por lo que no podemos garantizar una seguridad absoluta.

Cambios y contacto
Nos reservamos el derecho de actualizar esta Política de privacidad en cualquier momento. Los cambios se publicarán en esta página con una fecha actualizada de "Última actualización". Para cualquier consulta relacionada con la privacidad, comunícate con nuestro Oficial de Privacidad en primenode.corp@gmail.com.


privacy_pt.html



Política de Privacidade do LUVOA

Última atualização: 28 de junho de 2026

Introdução
A Prime Node ("Empresa", "nós") opera o aplicativo LUVOA. Consideramos a privacidade nossa prioridade máxima. Esta Política de Privacidade explica nossas diretrizes rigorosas em relação às informações que tratamos.

Arquitetura Híbrida Local-First e Política de Zero Registro (Zero-Log)
O LUVOA foi meticulosamente desenvolvido com base em um princípio de funcionamento integral no dispositivo (on-device) e tecnologia de zero registro.
- Isolamento Total de Dados: Configurações pessoais, frases favoritas e histórico de uso são armazenados exclusiva e integralmente no seu dispositivo local.
- Sem Armazenamento de Dados em Servidores: Nós NÃO transmitimos, coletamos ou armazenamos seus dados de uso pessoal, histórico de leitura ou frases favoritas em nossos servidores. Você mantém a propriedade e o controle totais sobre seus dados.
- Exclusão de Dados e Responsabilidade do Usuário: Como seus dados são armazenados localmente para garantir privacidade máxima, desinstalar o aplicativo LUVOA apagará de forma permanente e irrecuperável todos os dados salvos. Não mantemos cópias de backup em nenhum servidor e não podemos recuperar dados perdidos devido a troca de aparelho, perda, danos ou exclusão do app. O gerenciamento de backups do dispositivo é de responsabilidade exclusiva do usuário.

Coleta Limitada de Dados para Estabilidade do Serviço
Para fornecer uma experiência estável e garantir a integridade do aplicativo, podemos coletar estritamente dados anônimos e não identificáveis pessoalmente:
- Dados de Uso: Dados de diagnóstico anônimos (por exemplo, relatórios de erros/falhas) usados estritamente para aprimorar a estabilidade do aplicativo.

Serviços de Terceiros (Escopo Estritamente Limitado)
Para disponibilizar os recursos da assinatura VVIP e manter a infraestrutura essencial, utilizamos serviços terceirizados confiáveis vinculados a rígidos acordos de confidencialidade.
- Apple App Store e Google Play Services: Para distribuição do aplicativo e serviços estruturais essenciais.
- RevenueCat: Usado exclusivamente para processar compras no aplicativo com segurança e gerenciar assinaturas premium. Não coletamos, processamos ou armazenamos os dados do seu cartão de crédito ou informações financeiras.
- Firebase (Google): O serviço de envio de notificações push sem servidor FCM (Silent Message) é utilizado estritamente para emitir sinais leves e sem conteúdo textual para ativar o app em segundo plano, viabilizando a renderização instantânea de 0 ms integrada aos dados locais. Nenhuma informação de identificação pessoal é coletada ou transmitida durante esse processo.
- Supabase: Usado estritamente como infraestrutura de backend em modo "somente leitura" para implantar atualizações de conteúdo em tempo real (OTA) (frases, imagens de fundo, ícones) sem a necessidade de atualização pela loja de aplicativos. Seus dados pessoais (favoritos, marcadores, afirmações) NUNCA são transmitidos ou armazenados nos servidores do Supabase. Para prevenir totalmente o vazamento de dados, a segurança em nível de linha (RLS, Row Level Security) é rigorosamente aplicada em nossa infraestrutura.

Privacidade de Menores
O LUVOA é um aplicativo avançado desenvolvido para o público adulto. Restringimos estritamente nossos serviços a usuários menores de 14 anos. Não coletamos intencionalmente informações de identificação pessoal de menores de 14 anos. Caso tomemos conhecimento de que tais dados foram fornecidos, nós os excluiremos imediata e permanentemente de nossos sistemas.

Segurança dos Dados
Utilizamos medidas de segurança comercialmente aceitáveis e padrão do setor, incluindo segurança em nível de linha (RLS) e criptografia, para proteger quaisquer dados anônimos tratados por nossa infraestrutura. No entanto, nenhum método de armazenamento eletrônico ou transmissão pela internet é 100% seguro, e não podemos garantir segurança absoluta.

Alterações e Contato
Reservamo-nos o direito de atualizar esta Política de Privacidade a qualquer momento. Quaisquer alterações serão publicadas nesta página com a data de "Última atualização" revisada. Para qualquer dúvida relacionada à privacidade, entre em contato com nosso Encarregado de Proteção de Dados pelo e-mail primenode.corp@gmail.com.


privacy_vi.html



Chính sách Quyền riêng tư LUVOA

Cập nhật lần cuối: 28 tháng 6 năm 2026

Giới thiệu
Prime Node ("Công ty", "chúng tôi") vận hành ứng dụng LUVOA. Chúng tôi coi quyền riêng tư là ưu tiên cao nhất. Chính sách Quyền riêng tư này giải thích các nguyên tắc nghiêm ngặt của chúng tôi đối với thông tin mà chúng tôi xử lý.

Kiến trúc kết hợp Local-First & Chính sách không lưu nhật ký (Zero-Log)
LUVOA được thiết kế tỉ mỉ dựa trên nguyên tắc hoàn toàn trên thiết bị (on-device) và công nghệ không lưu nhật ký.
- Cách ly dữ liệu tuyệt đối: Cài đặt cá nhân, câu danh ngôn yêu thích và lịch sử sử dụng được lưu trữ hoàn toàn và độc quyền trên thiết bị cục bộ của bạn.
- Không lưu trữ dữ liệu trên máy chủ: Chúng tôi KHÔNG truyền tải, thu thập hoặc lưu trữ dữ liệu sử dụng cá nhân, lịch sử đọc hoặc câu danh ngôn yêu thích của bạn trên máy chủ của chúng tôi. Bạn giữ toàn quyền sở hữu và kiểm soát đối với dữ liệu của mình.
- Xóa dữ liệu và trách nhiệm của người dùng: Vì dữ liệu của bạn được lưu trữ cục bộ để đảm bảo quyền riêng tư tối đa, việc gỡ cài đặt ứng dụng LUVOA sẽ xóa vĩnh viễn và không thể khôi phục tất cả dữ liệu đã lưu. Chúng tôi không lưu giữ các bản sao lưu trên bất kỳ máy chủ nào và chúng tôi không thể khôi phục dữ liệu bị mất do nâng cấp thiết bị, mất mát, hư hỏng hoặc xóa ứng dụng. Việc quản lý các bản sao lưu thiết bị hoàn toàn là trách nhiệm của người dùng.

Thu thập dữ liệu giới hạn để duy trì tính ổn định của dịch vụ
Để cung cấp trải nghiệm mượt mà và đảm bảo tính ổn định của ứng dụng, chúng tôi chỉ có thể thu thập dữ liệu ẩn danh nghiêm ngặt, không mang tính nhận dạng cá nhân:
- Dữ liệu sử dụng: Dữ liệu chẩn đoán ẩn danh (ví dụ: nhật ký sự cố) được sử dụng nghiêm ngặt cho mục đích cải thiện tính ổn định của ứng dụng.

Dịch vụ của bên thứ ba (Phạm vi giới hạn nghiêm ngặt)
Để cung cấp các tính năng hội viên VVIP và duy trì cơ sở hạ tầng cốt lõi, chúng tôi sử dụng các dịch vụ bên thứ ba đáng tin cậy chịu sự ràng buộc của các thỏa thuận bảo mật nghiêm ngặt.
- Apple App Store & Google Play Services: Dành cho việc phân phối ứng dụng và các dịch vụ nền tảng cơ bản.
- RevenueCat: Được sử dụng độc quyền để xử lý các giao dịch mua hàng trong ứng dụng một cách an toàn và quản lý các gói đăng ký cao cấp. Chúng tôi không thu thập, xử lý hoặc lưu trữ thông tin thẻ tín dụng hoặc tài chính của bạn.
- Firebase (Google): Dịch vụ đẩy không máy chủ FCM (Silent Message) được sử dụng nghiêm ngặt để gửi các tín hiệu nhẹ (không có nội dung văn bản) nhằm đánh thức ứng dụng ở chế độ nền, kích hoạt khả năng hiển thị ngoại tuyến 0ms khớp với dữ liệu cục bộ. Không có thông tin nhận dạng cá nhân nào được thu thập hoặc truyền tải trong quá trình này.
- Supabase: Được sử dụng nghiêm ngặt như một cơ sở hạ tầng phụ trợ 'chỉ đọc' để triển khai các bản cập nhật nội dung ứng dụng trực tiếp qua mạng (OTA) (danh ngôn, hình nền, biểu tượng) mà không cần cập nhật qua kho ứng dụng. Dữ liệu cá nhân của bạn (yêu thích, dấu trang, khẳng định) KHÔNG BAO GIỜ được truyền đến hoặc lưu trữ trên máy chủ Supabase. Để ngăn chặn hoàn toàn việc rò rỉ dữ liệu, Bảo mật cấp hàng (RLS, Row Level Security) được áp dụng nghiêm ngặt cho cơ sở hạ tầng của chúng tôi.

Quyền riêng tư của trẻ em
LUVOA là ứng dụng nâng cao được thiết kế cho người dùng trưởng thành. Chúng tôi nghiêm cấm người dùng dưới 14 tuổi sử dụng dịch vụ của chúng tôi. Chúng tôi không cố ý thu thập thông tin nhận dạng cá nhân từ bất kỳ ai dưới 14 tuổi. Nếu chúng tôi phát hiện thông tin đó đã được cung cấp, chúng tôi sẽ ngay lập tức xóa vĩnh viễn thông tin đó khỏi hệ thống của mình.

Bảo mật dữ liệu
Chúng tôi sử dụng các biện pháp bảo mật tiêu chuẩn ngành và có thể chấp nhận được về mặt thương mại, bao gồm Bảo mật cấp hàng (RLS) và mã hóa, để bảo vệ bất kỳ dữ liệu ẩn danh nào được xử lý bởi cơ sở hạ tầng của chúng tôi. Tuy nhiên, không có phương pháp lưu trữ điện tử hoặc truyền tải qua internet nào là an toàn 100% và chúng tôi không thể đảm bảo an ninh tuyệt đối.

Thay đổi & Liên hệ
Chúng tôi có quyền cập nhật Chính sách Quyền riêng tư này bất kỳ lúc nào. Các thay đổi sẽ được đăng trên trang này cùng ngày "Cập nhật lần cuối" mới nhất. Mọi thắc mắc liên quan đến quyền riêng tư, vui lòng liên hệ với Cán bộ bảo vệ quyền riêng tư của chúng tôi tại primenode.corp@gmail.com.


privacy_de.html



LUVOA Datenschutzerklärung

Zuletzt aktualisiert: 28. Juni 2026

Einleitung
Prime Node („Unternehmen“, „wir“, „uns“) betreibt die LUVOA-Anwendung. Wir betrachten den Schutz der Privatsphäre als unsere höchste Priorität. Diese Datenschutzerklärung erläutert unsere strengen Richtlinien bezüglich der von uns verarbeiteten Informationen.

Local-First-Hybridarchitektur & Zero-Log-Richtlinie
LUVOA wurde sorgfältig nach einem vollständigen On-Device-Prinzip und einer Zero-Log-Technologie entwickelt.
- Absolute Datenisolation: Persönliche Einstellungen, Lieblingszitate und der Nutzungsverlauf werden vollständig und ausschließlich auf deinem lokalen Gerät gespeichert.
- Keine Datenspeicherung auf Servern: Wir übertragen, erfassen oder speichern deine persönlichen Nutzungsdaten, den Leseverlauf oder deine Lieblingszitate NICHT auf unseren Servern. Du behältst das vollständige Eigentum und die Kontrolle über deine Daten.
- Datenlöschung & Verantwortung des Nutzers: Da deine Daten für maximale Privatsphäre lokal gespeichert werden, führt das Löschen der LUVOA-App dazu, dass alle gespeicherten Daten dauerhaft und unwiederbringlich gelöscht werden. Wir bewahren keine Sicherungskopien auf Servern auf und können Daten, die durch Gerätewechsel, Verlust, Beschädigung oder App-Löschung verloren gegangen sind, nicht wiederherstellen. Die Verwaltung von Gerätesicherungen liegt allein in der Verantwortung des Nutzers.

Eingeschränkte Datenerfassung für die Dienststabilität
Um ein reibungsloses Erlebnis zu bieten und die Stabilität der App zu gewährleisten, erfassen wir unter Umständen streng anonymisierte, nicht personenbezogene Daten:
- Nutzungsdaten: Anonyme Diagnosedaten (z. B. Absturzberichte), die ausschließlich zur Verbesserung der App-Stabilität verwendet werden.

Dienste von Drittanbietern (Streng begrenzter Umfang)
Um Funktionen der VVIP-Mitgliedschaft bereitzustellen und die Kerninfrastruktur aufrechtzuerhalten, nutzen wir vertrauenswürdige Dienste von Drittanbietern, die an strenge Vertraulichkeitsvereinbarungen gebunden sind.
- Apple App Store & Google Play Services: Für die App-Verteilung und grundlegende Systemdienste.
- RevenueCat: Wird ausschließlich zur sicheren Abwicklung von In-App-Käufen und zur Verwaltung von Premium-Abonnements verwendet. Wir erfassen, verarbeiten oder speichern deine Kreditkarten- oder Finanzdaten nicht.
- Firebase (Google): FCM Serverless Push (Silent Message) wird streng dazu verwendet, leichte Signale (ohne Textinhalte) zu senden, um die App im Hintergrund aufzuwecken und ein sofortiges Offline-Rendering von 0 ms mit lokalen Daten zu ermöglichen. Während dieses Vorgangs werden keine personenbezogenen Daten erfasst oder übertragen.
- Supabase: Wird streng als „schreibgeschützte“ (Read-Only) Backend-Infrastruktur verwendet, um Over-The-Air-Updates (OTA) für App-Inhalte (Zitate, Hintergrundbilder, Symbole) bereitzustellen, ohne dass ein Store-Update erforderlich ist. Deine persönlichen Daten (Favoriten, Lesezeichen, Affirmationen) werden NIEMALS an Supabase-Server übertragen oder dort gespeichert. Um Datendiebstahl vollständig zu verhindern, wird die Sicherheit auf Zeilenebene (Row Level Security, RLS) auf unserer Infrastruktur streng angewendet.

Schutz der Privatsphäre von Kindern
LUVOA ist eine fortschrittliche Anwendung, die für erwachsene Nutzer entwickelt wurde. Wir beschränken unsere Dienste strikt auf Nutzer ab 14 Jahren. Wir erfassen wissentlich keine personenbezogenen Daten von Personen unter 14 Jahren. Wenn wir feststellen, dass uns solche Informationen bereitgestellt wurden, werden wir diese unverzüglich und dauerhaft aus unseren Systemen löschen.

Datensicherheit
Wir setzen kommerziell akzeptable, branchenübliche Sicherheitsmaßnahmen ein, einschließlich Sicherheit auf Zeilenebene (RLS) und Verschlüsselung, um alle von unserer Infrastruktur verarbeiteten anonymisierten Daten zu schützen. Keine Methode der elektronischen Speicherung oder Übertragung über das Internet ist jedoch zu 100 % sicher, und wir können keine absolute Sicherheit garantieren.

Änderungen & Kontakt
Wir behalten uns das Recht vor, diese Datenschutzerklärung jederzeit zu aktualisieren. Änderungen werden auf dieser Seite mit einem aktualisierten Datum „Zuletzt aktualisiert“ veröffentlicht. Bei Fragen zum Datenschutz wende dich bitte an unseren Datenschutzbeauftragten unter primenode.corp@gmail.com.


privacy_fr.html



Politique de confidentialité de LUVOA

Dernière mise à jour : 28 juin 2026

Introduction
Prime Node (« Société », « nous ») exploite l'application LUVOA. Nous considérons la protection de la vie privée comme notre priorité absolue. Cette Politique de confidentialité détaille nos directives strictes concernant les informations que nous traitons.

Architecture hybride Local-First et politique de zéro journalisation (Zero-Log)
LUVOA est méticuleusement conçu selon un principe d'exécution intégrale sur l'appareil (on-device) et une technologie de zéro journalisation.
- Isolation absolue des données : Les paramètres personnels, les citations favorites et l'historique d'utilisation sont stockés intégralement et exclusivement sur votre appareil local.
- Aucun stockage de données sur des serveurs : Nous ne transmettons, ne collectons et ne stockons AUCUNE de vos données d'utilisation personnelles, historique de lecture ou citations favorites sur nos serveurs. Vous conservez l'entière propriété et le contrôle total de vos données.
- Suppression des données et responsabilité de l'utilisateur : Vos données étant stockées localement pour garantir une confidentialité maximale, la désinstallation de l'application LUVOA entraînera la suppression définitive et irréversible de toutes les données enregistrées. Nous ne conservons aucune copie de sauvegarde sur aucun serveur et ne pouvons pas récupérer les données perdues en raison d'un changement d'appareil, d'une perte, de dommages ou de la suppression de l'application. La gestion des sauvegardes de l'appareil relève exclusivement de la responsabilité de l'utilisateur.

Collecte limitée de données pour la stabilité du service
Pour offrir une expérience fluide et assurer la stabilité de l'application, nous pouvons collecter des données strictement anonymisées et non personnellement identifiables :
- Données d'utilisation : Données de diagnostic anonymes (par exemple, rapports de plantage) strictement utilisées pour améliorer la stabilité de l'application.

Services tiers (Champ d'application strictement limité)
Pour fournir les fonctionnalités de l'adhésion VVIP et maintenir l'infrastructure essentielle, nous faisons appel à des services tiers de confiance soumis à des accords de confidentialité stricts.
- Apple App Store et Google Play Services : Pour la distribution de l'application et les services système fondamentaux.
- RevenueCat : Utilisé exclusivement pour traiter les achats intégrés en toute sécurité et gérer les abonnements premium. Nous ne collectons, ne traitons et ne stockons pas les informations de votre carte de crédit ou vos données financières.
- Firebase (Google) : Le service de notifications push sans serveur FCM (Silent Message) est strictement utilisé pour envoyer des signaux légers (sans contenu textuel) afin de réveiller l'application en arrière-plan, permettant un rendu hors ligne instantané de 0 ms synchronisé avec les données locales. Aucune information personnellement identifiable n'est collectée ou transmise au cours de ce processus.
- Supabase : Utilisé strictement comme une infrastructure backend en « lecture seule » pour déployer des mises à jour de contenu en direct (OTA) (citations, images d'arrière-plan, icônes) sans nécessiter de mise à jour sur le store. Vos données personnelles (favoris, signets, affirmations) ne sont JAMAIS transmises ni stockées sur les serveurs de Supabase. Pour empêcher totalement toute fuite de données, la sécurité au niveau des lignes (Row Level Security, RLS) est rigoureusement appliquée sur notre infrastructure.

Protection de la vie privée des enfants
LUVOA est une application avancée conçue pour les utilisateurs adultes. Nous limitons strictement nos services aux personnes âgées d'au moins 14 ans. Nous ne collectons pas sciemment d'informations personnellement identifiables auprès de personnes de moins de 14 ans. Si nous constatons que de telles informations nous ont été fournies, nous les supprimerons immédiatement et définitivement de nos systèmes.

Sécurité des données
Nous utilisons des mesures de sécurité standard et commercialement acceptables, y compris la sécurité au niveau des lignes (RLS) et le chiffrement, pour protéger toute donnée anonymisée traitée par notre infrastructure. Cependant, aucune méthode de stockage électronique ou de transmission sur Internet n'est sûre à 100 %, et nous ne pouvons garantir une sécurité absolue.

Modifications et contact
Nous nous réservons le droit de mettre à jour cette Politique de confidentialité à tout moment. Les modifications seront publiées sur cette page avec une date de « Dernière mise à jour » révisée. Pour toute question relative à la confidentialité, veuillez contacter notre Délégué à la protection des données à primenode.corp@gmail.com.


privacy_hi.html



LUVOA गोपनीयता नीति

अंतिम अपडेट: 28 जून, 2026

परिचय
Prime Node ("कंपनी", "हम", "हमें") LUVOA एप्लिकेशन का संचालन करता है। हम गोपनीयता को अपनी सर्वोच्च प्राथमिकता मानते हैं। यह गोपनीयता नीति हमारे द्वारा संसाधित की जाने वाली जानकारी के संबंध में हमारे सख्त दिशानिर्देशों की व्याख्या करती है।

लोकल-फर्स्ट हाइब्रिड आर्किटेक्चर और ज़ीरो-लॉग नीति
LUVOA को पूरी तरह से ऑन-डिवाइस सिद्धांत और ज़ीरो-लॉग तकनीक पर सावधानीपूर्वक विकसित किया गया है।
- पूर्ण डेटा अलगाव: व्यक्तिगत सेटिंग्स, पसंदीदा विचार और उपयोग का इतिहास पूरी तरह और विशेष रूप से आपके स्थानीय डिवाइस पर संग्रहीत होते हैं।
- सर्वर पर कोई डेटा भंडारण नहीं: हम अपने सर्वर पर आपके व्यक्तिगत उपयोग डेटा, पढ़ने के इतिहास या पसंदीदा विचारों को प्रेषित, एकत्र या संग्रहीत नहीं करते हैं। आप अपने डेटा पर पूर्ण स्वामित्व और नियंत्रण बनाए रखते हैं।
- डेटा विलोपन और उपयोगकर्ता की जिम्मेदारी: चूंकि अधिकतम गोपनीयता के लिए आपका डेटा स्थानीय रूप से संग्रहीत किया जाता है, इसलिए LUVOA ऐप को हटाने से सभी संग्रहीत डेटा स्थायी रूप से और अपूरणीय रूप से मिट जाएगा। हम किसी भी सर्वर पर बैकअप प्रतियां नहीं रखते हैं, और हम डिवाइस अपग्रेड, हानि, क्षति या ऐप विलोपन के कारण खोए हुए डेटा को पुनर्प्राप्त नहीं कर सकते हैं। डिवाइस बैकअप का प्रबंधन पूरी तरह से उपयोगकर्ता की जिम्मेदारी है।

सेवा स्थिरता के लिए सीमित डेटा संग्रह
एक निर्बाध अनुभव प्रदान करने और ऐप स्थिरता सुनिश्चित करने के लिए, हम सख्ती से अज्ञात, गैर-व्यक्तिगत रूप से पहचान योग्य डेटा एकत्र कर सकते हैं:
- उपयोग डेटा: ऐप की स्थिरता में सुधार के लिए सख्ती से उपयोग किया जाने वाला अज्ञात डायग्नोस्टिक डेटा (उदा. क्रैश लॉग)।

तृतीय-पक्ष सेवाएं (सख्ती से सीमित दायरा)
VVIP सदस्यता सुविधाएं प्रदान करने और मुख्य बुनियादी ढांचे को बनाए रखने के लिए, हम सख्त गोपनीयता समझौतों से बंधी विश्वसनीय तृतीय-पक्ष सेवाओं का उपयोग करते हैं।
- Apple App Store और Google Play Services: ऐप वितरण और मूलभूत सेवाओं के लिए।
- RevenueCat: इन-ऐप खरीदारी को सुरक्षित रूप से संसाधित करने और प्रीमियम सदस्यताओं को प्रबंधित करने के लिए विशेष रूप से उपयोग किया जाता है। हम आपके क्रेडिट कार्ड या वित्तीय जानकारी को एकत्र, संसाधित या संग्रहीत नहीं करते हैं।
- Firebase (Google): FCM सर्वरलेस पुश (साइलेंट मैसेज) का उपयोग केवल हल्के खाली सिग्नल (भारी टेक्स्ट सामग्री के बिना) भेजने के लिए किया जाता है ताकि ऐप को बैकग्राउंड में सक्रिय किया जा सके, जिससे स्थानीय डेटा के साथ 0ms का ऑफलाइन रेंडरिंग सक्षम हो सके। इस प्रक्रिया के दौरान कोई भी व्यक्तिगत पहचान योग्य जानकारी एकत्र या प्रेषित नहीं की जाती है।
- Supabase: स्टोर अपडेट की आवश्यकता के बिना ऐप सामग्री (विचार, पृष्ठभूमि चित्र, आइकन) के लिए ओवर-द-एयर (OTA) अपडेट तैनात करने के लिए सख्ती से 'केवल-पढ़ने योग्य' बैकएंड इंफ्रास्ट्रक्चर के रूप में उपयोग किया जाता है। आपका व्यक्तिगत डेटा (पसंदीदा, बुकमार्क, सकारात्मक पुष्टि) कभी भी Supabase सर्वर पर प्रेषित या संग्रहीत नहीं किया जाता है। डेटा चोरी को पूरी तरह से रोकने के लिए, हमारे इंफ्रास्ट्रक्चर पर रो लेवल सिक्योरिटी (RLS) को सख्ती से लागू किया गया है।

बच्चों की गोपनीयता
LUVOA वयस्क उपयोगकर्ताओं के लिए डिज़ाइन किया गया एक उन्नत एप्लिकेशन है। हम 14 वर्ष से कम आयु के उपयोगकर्ताओं के लिए अपनी सेवाओं को सख्ती से प्रतिबंधित करते हैं। हम जानबूझकर 14 वर्ष से कम आयु के किसी भी व्यक्ति से व्यक्तिगत पहचान योग्य जानकारी एकत्र नहीं करते हैं। यदि हमें पता चलता है कि ऐसी जानकारी प्रदान की गई है, तो हम इसे तुरंत और स्थायी रूप से अपने सिस्टम से हटा देंगे।

डेटा सुरक्षा
हम अपने बुनियादी ढांचे द्वारा प्रबंधित किसी भी अज्ञात डेटा की सुरक्षा के लिए रो लेवल सिक्योरिटी (RLS) और एन्क्रिप्शन सहित व्यावसायिक रूप से स्वीकार्य, उद्योग-मानक सुरक्षा उपायों का उपयोग करते हैं। हालांकि, इलेक्ट्रॉनिक भंडारण या इंटरनेट पर ट्रांसमिशन का कोई भी तरीका 100% सुरक्षित नहीं है, और हम पूर्ण सुरक्षा की गारंटी नहीं दे सकते।

परिवर्तन और संपर्क
हम किसी भी समय इस गोपनीयता नीति को अपडेट करने का अधिकार सुरक्षित रखते हैं। परिवर्तन इस पृष्ठ पर एक अद्यतन "अंतिम अपडेट" तिथि के साथ पोस्ट किए जाएंगे। किसी भी गोपनीयता से संबंधित पूछताछ के लिए, कृपया हमारे गोपनीयता अधिकारी से primenode.corp@gmail.com पर संपर्क करें।


privacy_zh_cn.html



LUVOA 隐私政策

最后更新日期: 2026年6月28日

引言
Prime Node（以下简称“公司”或“我们”）负责运营 LUVOA 应用程序。我们始终将保护用户隐私置于最高优先级。本隐私政策旨在向您说明我们处理相关信息时的严格准则。

端侧优先（Local-First）混合架构与零日志（Zero-Log）政策
LUVOA 严格遵循完全基于设备端（On-device）原则与零日志技术精心构建。
- 绝对的数据隔离: 您的个人偏好设置、收藏的名言以及浏览历史均完全且仅保存在您的本地设备中。
- 服务器绝无数据留存: 我们绝不会在服务器端传输、收集或存储您的个人使用数据、阅读历史或收藏名言。您对自己的所有数据拥有完全的所有权与控制权。
- 数据删除与用户责任: 为实现最高级别的隐私保护，所有数据均存放于本地，因此卸载 LUVOA 应用将永久且不可逆地清除所有已保存的数据。我们不会在任何服务器上保留备份副本，亦无法找回因更换设备、遗失、损坏或卸载应用而丢失的数据。设备数据的备份与管理完全属于用户的个人责任。

保障服务稳定性所需的最低限度数据收集
为提供流畅的使用体验并确保应用的稳定性，我们仅可能会收集严格匿名化且无法识别个人身份的数据：
- 使用数据: 严格用于优化和提升应用稳定性的匿名诊断数据（如崩溃日志 Crash Logs）。

第三方服务提供商（严格限制使用范围）
为提供 VVIP 会员权益并维护核心基础设施运行，我们接入了受严格保密协议约束的可信第三方服务：
- Apple App Store 与 Google Play Services: 用于应用的官方分发及基础系统服务支持。
- RevenueCat: 仅用于安全处理应用内购买（In-App Purchase）及管理高级会员订阅。我们绝不会直接收集、处理或存储您的信用卡信息或任何财务账户数据。
- Firebase (Google): FCM 无服务器静默推送（Silent Message）严格仅用于向设备发送无文本内容的轻量信号以唤醒后台应用，从而实现与本地数据毫秒级匹配的 0ms 即时离线渲染。在此过程中绝不收集或传输任何个人身份信息。
- Supabase: 严格作为“只读（Read-Only）”后端基础设施，用于向客户端热更新（OTA）应用内容（名言库、背景图、图标素材），无需通过应用商店发布更新。您的个人数据（收藏夹、书签、肯定语等）绝不会传输或存储至 Supabase 服务器。为彻底杜绝数据安全隐患，我们的基础设施全面启用了行级安全策略（Row Level Security, RLS）。

未成年人隐私保护
LUVOA 是一款面向成年用户打造的高品质应用程序。我们严格限制未满 14 周岁的未成年人使用本服务。我们绝不会故意收集未满 14 周岁未成年人的个人身份信息。若发现无意中获取了此类信息，我们将立即从系统中予以永久删除。

数据安全保障
我们采用行业标准且商业上合理的安全措施，包括行级安全（RLS）和高强度数据加密技术，以保护由我们基础设施处理的任何匿名化数据。但请注意，互联网上的任何电子存储或数据传输方式均无法做到 100% 绝对安全，因此我们无法提供绝对的安全担保。

政策变更与联系方式
我们保留随时更新本隐私政策的权利。任何修订均会更新本页面顶部的“最后更新日期”并予以公布。如对隐私政策有任何疑问，请联系我们的隐私保护专员：primenode.corp@gmail.com。


privacy_zh_tw.html



LUVOA 隱私權政策

最後更新日期: 2026年6月28日

引言
Prime Node（以下簡稱「公司」或「我們」）負責營運 LUVOA 應用程式。我們始終將保護使用者隱私置於最高優先順序。本隱私權政策旨在向您說明我們處理相關資訊時的嚴格準則。

端側優先（Local-First）混合架構與零記錄（Zero-Log）政策
LUVOA 嚴格遵循完全基於裝置端（On-device）原則與零記錄技術精心構建。
- 絕對的資料隔離: 您的個人偏好設定、收藏的名言以及瀏覽歷史均完全且僅保存在您的本機裝置中。
- 伺服器絕無資料留存: 我們絕不會在伺服器端傳輸、收集或儲存您的個人使用資料、閱讀歷史或收藏名言。您對自己的所有資料擁有完全的所有權與控制權。
- 資料刪除與使用者責任: 為實現最高級別的隱私保護，所有資料均存放於本機，因此解除安裝 LUVOA 應用程式將永久且不可逆地清除所有已儲存的資料。我們不會在任何伺服器上保留備份複本，亦無法找回因更換裝置、遺失、損壞或解除安裝應用程式而遺失的資料。裝置資料的備份與管理完全屬於使用者的個人責任。

保障服務穩定性所需的最低限度資料收集
為提供流暢的使用體驗並確保應用程式的穩定性，我們僅可能會收集嚴格匿名化且無法識別個人身分的資料：
- 使用資料: 嚴格用於最佳化和提升應用程式穩定性的匿名診斷資料（如當機記錄 Crash Logs）。

第三方服務提供商（嚴格限制使用範圍）
為提供 VVIP 會員權益並維護核心基礎設施運行，我們接入了受嚴格保密協議約束的可信第三方服務：
- Apple App Store 與 Google Play Services: 用於應用程式的官方發布及基礎系統服務支援。
- RevenueCat: 僅用於安全處理應用程式內購買（In-App Purchase）及管理高級會員訂閱。我們絕不會直接收集、處理或儲存您的信用卡資訊或任何財務帳戶資料。
- Firebase (Google): FCM 無伺服器靜音推播（Silent Message）嚴格僅用於向裝置發送無文字內容的輕量訊號以喚醒後台應用程式，從而實現與本機資料毫秒級匹配的 0ms 即時離線渲染。在此過程中絕不收集或傳輸任何個人身分資訊。
- Supabase: 嚴格作為「唯讀（Read-Only）」後端基礎設施，用於向客戶端即時更新（OTA）應用程式內容（名言庫、背景圖、圖示素材），無需透過應用程式商店發布更新。您的個人資料（收藏夾、書籤、肯定語等）絕不會傳輸或儲存至 Supabase 伺服器。為徹底杜絕資料安全隱患，我們的基礎設施全面啟用了資料列級安全策略（Row Level Security, RLS）。

未成年人隱私保護
LUVOA 是一款面向成年使用者打造的高品質應用程式。我們嚴格限制未滿 14 歲的未成年人使用本服務。我們絕不會故意收集未滿 14 歲未成年人的個人身分資訊。若發現無意中獲取了此類資訊，我們將立即從系統中予以永久刪除。

資料安全保障
我們採用行業標準且商業上合理的安全措施，包括資料列級安全（RLS）和高強度資料加密技術，以保護由我們基礎設施處理的任何匿名化資料。但請注意，網際網路上的任何電子儲存或資料傳輸方式均無法做到 100% 絕對安全，因此我們無法提供絕對的安全擔保。

政策變更與聯絡方式
我們保留隨時更新本隱私權政策的權利。任何修訂均會更新本頁面頂部的「最後更新日期」並予以公布。如對隱私權政策有任何疑問，請聯絡我們的隱私保護專員：primenode.corp@gmail.com。


privacy_ru.html

Политика конфиденциальности LUVOA

Последнее обновление: 28 июня 2026 г.

Введение
Компания Prime Node («Компания», «мы») управляет приложением LUVOA. Мы считаем защиту конфиденциальности нашим наивысшим приоритетом. Настоящая Политика конфиденциальности разъясняет наши строгие правила в отношении обрабатываемой нами информации.

Гибридная архитектура Local-First и политика отсутствия логов (Zero-Log)
Приложение LUVOA тщательно разработано на основе принципа полной локальной работы на устройстве (on-device) и технологии нулевого логирования.
- Абсолютная изоляция данных: Персональные настройки, избранные цитаты и история использования хранятся исключительно на вашем локальном устройстве.
- Отсутствие хранения данных на серверах: Мы НЕ передаем, не собираем и не храним ваши личные данные об использовании, историю чтения или избранные цитаты на наших серверах. Вы сохраняете полное право собственности и контроль над своими данными.
- Удаление данных и ответственность пользователя: Поскольку ваши данные хранятся локально для обеспечения максимальной конфиденциальности, удаление приложения LUVOA приведет к безвозвратному и окончательному удалению всех сохраненных данных. Мы не храним резервные копии на серверах и не можем восстановить данные, утраченные из-за смены устройства, утери, повреждения или удаления приложения. Управление резервным копированием устройства является исключительно обязанностью пользователя.

Ограниченный сбор данных для стабильности сервиса
Для обеспечения стабильной работы приложения и повышения удобства использования мы можем собирать строго анонимизированные данные, не позволяющие идентифицировать личность:
- Данные об использовании: Анонимные диагностические данные (например, журналы сбоев), используемые исключительно для повышения стабильности приложения.

Сторонние сервисы (Строго ограниченный объем)
Для предоставления функций членства VVIP и поддержания основной инфраструктуры мы используем надежные сторонние сервисы, связанные строгими соглашениями о конфиденциальности.
- Apple App Store и Google Play Services: Для распространения приложения и базовых системных сервисов.
- RevenueCat: Используется исключительно для безопасной обработки встроенных покупок и управления премиум-подписками. Мы не собираем, не обрабатываем и не храним данные вашей кредитной карты или финансовую информацию.
- Firebase (Google): Бессерверные push-уведомления FCM (Silent Message) используются исключительно для отправки легких сигналов (без текстового содержимого) для пробуждения приложения в фоновом режиме, что обеспечивает мгновенный оффлайн-рендеринг 0 мс на основе локальных данных. В ходе этого процесса никакая личная информация не собирается и не передается.
- Supabase: Используется исключительно в качестве «только для чтения» (Read-Only) бэкенд-инфраструктуры для доставки обновлений контента по воздуху (OTA) (цитаты, фоновые изображения, иконки) без необходимости обновления через магазин приложений. Ваши персональные данные (избранное, закладки, аффирмации) НИКОГДА не передаются и не хранятся на серверах Supabase. Для полного предотвращения утечки данных к нашей инфраструктуре строго применяется безопасность на уровне строк (Row Level Security, RLS).

Конфиденциальность детей
LUVOA — это приложение, разработанное для совершеннолетних пользователей. Мы строго ограничиваем доступ к нашим услугам лицам младше 14 лет. Мы сознательно не собираем личную информацию от лиц младше 14 лет. Если нам станет известно, что такая информация была предоставлена, мы немедленно и безвозвратно удалим ее из наших систем.

Безопасность данных
Мы используем коммерчески приемлемые, стандартные для отрасли меры безопасности, включая безопасность на уровне строк (RLS) и шифрование, для защиты любых анонимизированных данных, обрабатываемых нашей инфраструктурой. Однако ни один метод электронного хранения или передачи через Интернет не является на 100% безопасным, и мы не можем гарантировать абсолютную безопасность.

Изменения и контакты
Мы оставляем за собой право обновлять настоящую Политику конфиденциальности в любое время. Изменения будут опубликованы на этой странице с обновленной датой «Последнее обновление». По любым вопросам, связанным с конфиденциальностью, обращайтесь к нашему сотруднику по защите данных по адресу primenode.corp@gmail.com.


privacy_id.html

Kebijakan Privasi LUVOA

Terakhir Diperbarui: 28 Juni 2026

Pengantar
Prime Node ("Perusahaan", "kami") mengoperasikan aplikasi LUVOA. Kami menganggap privasi sebagai prioritas tertinggi kami. Kebijakan Privasi ini menjelaskan pedoman ketat kami terkait informasi yang kami tangani.

Arsitektur Hibrida Local-First & Kebijakan Nol-Log (Zero-Log)
LUVOA dirancang secara presisi berdasarkan prinsip menyeluruh pada perangkat (on-device) dan teknologi nol-log.
- Isolasi Data Mutlak: Pengaturan pribadi, kutipan favorit, dan riwayat penggunaan disimpan secara utuh dan eksklusif di perangkat lokal Anda.
- Tidak Ada Penyimpanan Data di Server: Kami TIDAK mengirimkan, mengumpulkan, atau menyimpan data penggunaan pribadi, riwayat membaca, atau kutipan favorit Anda di server kami. Anda memegang kepemilikan dan kendali penuh atas data Anda.
- Penghapusan Data & Tanggung Jawab Pengguna: Karena data Anda disimpan secara lokal untuk privasi maksimal, menghapus aplikasi LUVOA akan menghapus semua data yang tersimpan secara permanen dan tidak dapat dipulihkan. Kami tidak menyimpan salinan cadangan di server mana pun, dan kami tidak dapat memulihkan data yang hilang karena penggantian perangkat, kehilangan, kerusakan, atau penghapusan aplikasi. Mengelola pencadangan perangkat sepenuhnya merupakan tanggung jawab pengguna.

Pengumpulan Data Terbatas untuk Stabilitas Layanan
Untuk memberikan pengalaman yang lancar dan memastikan stabilitas aplikasi, kami hanya dapat mengumpulkan data yang benar-benar dianonimkan dan tidak dapat diidentifikasi secara pribadi:
- Data Penggunaan: Data diagnostik anonim (misalnya, log kerusakan) yang digunakan secara ketat untuk meningkatkan stabilitas aplikasi.

Layanan Pihak Ketiga (Cakupan yang Sangat Terbatas)
Untuk menyediakan fitur keanggotaan VVIP dan memelihara infrastruktur inti, kami menggunakan layanan pihak ketiga tepercaya yang terikat oleh perjanjian kerahasiaan yang ketat.
- Apple App Store & Google Play Services: Untuk distribusi aplikasi dan layanan sistem mendasar.
- RevenueCat: Digunakan secara eksklusif untuk memproses pembelian dalam aplikasi secara aman dan mengelola langganan premium. Kami tidak mengumpulkan, memproses, atau menyimpan informasi kartu kredit atau keuangan Anda.
- Firebase (Google): FCM Serverless Push (Silent Message) digunakan secara ketat untuk mengirimkan sinyal ringan tanpa teks untuk mengaktifkan aplikasi di latar belakang, memungkinkan perenderan offline instan 0ms yang dicocokkan dengan data lokal. Tidak ada informasi identitas pribadi yang dikumpulkan atau dikirimkan selama proses ini.
- Supabase: Digunakan secara ketat sebagai infrastruktur backend 'hanya baca' (Read-Only) untuk menyebarkan pembaruan konten aplikasi Over-The-Air (OTA) (kutipan, gambar latar belakang, ikon) tanpa memerlukan pembaruan di toko aplikasi. Data pribadi Anda (favorit, markah, afirmasi) TIDAK PERNAH dikirimkan ke atau disimpan di server Supabase. Untuk mencegah kebocoran data sepenuhnya, Keamanan Tingkat Baris (Row Level Security, RLS) diterapkan secara ketat pada infrastruktur kami.

Privasi Anak-Anak
LUVOA adalah aplikasi tingkat lanjut yang dirancang untuk pengguna dewasa. Kami secara ketat membatasi layanan kami dari pengguna di bawah usia 14 tahun. Kami tidak secara sengaja mengumpulkan informasi identitas pribadi dari siapa pun yang berusia di bawah 14 tahun. Jika kami mengetahui bahwa informasi tersebut telah diberikan, kami akan segera dan menghapusnya secara permanen dari sistem kami.

Keamanan Data
Kami menggunakan langkah-langkah keamanan standar industri yang dapat diterima secara komersial, termasuk Keamanan Tingkat Baris (RLS) dan enkripsi, untuk melindungi data anonim apa pun yang ditangani oleh infrastruktur kami. Namun, tidak ada metode penyimpanan elektronik atau transmisi melalui internet yang 100% aman, dan kami tidak dapat menjamin keamanan mutlak.

Perubahan & Kontak
Kami berhak memperbarui Kebijakan Privasi ini kapan saja. Perubahan akan diposting di halaman ini dengan tanggal "Terakhir Diperbarui" yang diperbarui. Untuk pertanyaan terkait privasi, silakan hubungi Petugas Privasi kami di primenode.corp@gmail.com.


privacy_th.html

นโยบายความเป็นส่วนตัวของ LUVOA

อัปเดตล่าสุด: 28 มิถุนายน 2026

บทนำ
Prime Node ("บริษัท", "เรา") เป็นผู้ดำเนินการแอปพลิเคชัน LUVOA เราถือว่าความเป็นส่วนตัวเป็นสิ่งที่สำคัญที่สุด นโยบายความเป็นส่วนตัวนี้จะอธิบายถึงแนวทางปฏิบัติที่เข้มงวดของเราเกี่ยวกับข้อมูลที่เราจัดการ

สถาปัตยกรรมไฮบริด Local-First และนโยบายไม่บันทึกข้อมูล (Zero-Log)
LUVOA ได้รับการออกแบบทางวิศวกรรมอย่างพิถีพิถันบนหลักการทำงานบนอุปกรณ์ทั้งหมด (on-device) และเทคโนโลยีที่ไม่บันทึกข้อมูลการใช้งาน
- การแยกข้อมูลอย่างสมบูรณ์: การตั้งค่าส่วนบุคคล คำคมที่ชอบ และประวัติการใช้งานจะถูกจัดเก็บไว้ในอุปกรณ์ของคุณเท่านั้น
- ไม่มีการจัดเก็บข้อมูลบนเซิร์ฟเวอร์: เราไม่ส่ง รวบรวม หรือจัดเก็บข้อมูลการใช้งานส่วนบุคคล ประวัติการอ่าน หรือคำคมที่ชื่นชอบของคุณไว้บนเซิร์ฟเวอร์ของเรา คุณยังคงมีความเป็นเจ้าของและสามารถควบคุมข้อมูลของคุณได้อย่างสมบูรณ์
- การลบข้อมูลและความรับผิดชอบของผู้ใช้: เนื่องจากข้อมูลของคุณถูกจัดเก็บไว้ในเครื่องเพื่อความเป็นส่วนตัวสูงสุด การลบแอป LUVOA จะเป็นการลบข้อมูลที่จัดเก็บไว้ทั้งหมดอย่างถาวรและไม่สามารถกู้คืนได้ เราไม่ได้เก็บสำเนาสำรองไว้บนเซิร์ฟเวอร์ใดๆ และเราไม่สามารถกู้คืนข้อมูลที่สูญหายเนื่องจากการเปลี่ยนอุปกรณ์ การสูญหาย ความเสียหาย หรือการลบแอปได้ การจัดการการสำรองข้อมูลของอุปกรณ์ถือเป็นความรับผิดชอบของผู้ใช้แต่เพียงผู้เดียว

การรวบรวมข้อมูลอย่างจำกัดเพื่อความเสถียรของบริการ
เพื่อมอบประสบการณ์ที่ราบรื่นและรับรองความเสถียรของแอป เราอาจรวบรวมข้อมูลที่ไม่สามารถระบุตัวบุคคลได้และเป็นข้อมูลที่ไม่เปิดเผยตัวตนอย่างเคร่งครัด:
- ข้อมูลการใช้งาน: ข้อมูลการวินิจฉัยที่ไม่ระบุตัวตน (เช่น บันทึกการขัดข้อง) ซึ่งใช้เพื่อปรับปรุงความเสถียรของแอปเท่านั้น

บริการของบุคคลที่สาม (ขอบเขตที่จำกัดอย่างเคร่งครัด)
เพื่อมอบคุณสมบัติการเป็นสมาชิก VVIP และรักษาโครงสร้างพื้นฐานหลัก เราใช้บริการของบุคคลที่สามที่เชื่อถือได้ซึ่งผูกพันตามข้อตกลงการรักษาความลับที่เข้มงวด
- Apple App Store และ Google Play Services: สำหรับการเผยแพร่แอปและบริการระบบพื้นฐาน
- RevenueCat: ใช้สำหรับการประมวลผลการซื้อภายในแอปอย่างปลอดภัยและจัดการการสมัครสมาชิกพรีเมียมเท่านั้น เราไม่รวบรวม ประมวลผล หรือจัดเก็บข้อมูลบัตรเครดิตหรือข้อมูลทางการเงินของคุณ
- Firebase (Google): การแจ้งเตือนแบบพุชไร้เซิร์ฟเวอร์ FCM (Silent Message) ถูกใช้เพื่อส่งสัญญาณขนาดเบาที่ไม่มีข้อความ เพื่อปลุกแอปในพื้นหลัง ทำให้สามารถเรนเดอร์ข้อมูลออฟไลน์ได้ทันที 0ms ให้ตรงกับข้อมูลในเครื่อง ไม่มีการรวบรวมหรือส่งข้อมูลที่สามารถระบุตัวตนได้ในระหว่างกระบวนการนี้
- Supabase: ใช้เป็นโครงสร้างพื้นฐานแบ็กเอนด์แบบ 'อ่านอย่างเดียว' (Read-Only) เพื่อปรับใช้การอัปเดตเนื้อหาแอปแบบ Over-The-Air (OTA) (คำคม, รูปภาพพื้นหลัง, ไอคอน) โดยไม่ต้องอัปเดตผ่านสโตร์ ข้อมูลส่วนบุคคลของคุณ (รายการโปรด, ที่คั่นหน้า, คำยืนยัน) จะไม่ถูกส่งไปยังหรือจัดเก็บไว้บนเซิร์ฟเวอร์ Supabase อย่างเด็ดขาด เพื่อป้องกันการรั่วไหลของข้อมูลอย่างสมบูรณ์ ความปลอดภัยระดับแถว (Row Level Security, RLS) จึงถูกนำมาใช้อย่างเข้มงวดกับโครงสร้างพื้นฐานของเรา

ความเป็นส่วนตัวของเด็ก
LUVOA เป็นแอปพลิเคชันขั้นสูงที่ออกแบบมาสำหรับผู้ใช้ที่เป็นผู้ใหญ่ เราจำกัดการให้บริการแก่ผู้ใช้ที่มีอายุต่ำกว่า 14 ปีอย่างเคร่งครัด เราไม่ได้รวบรวมข้อมูลที่สามารถระบุตัวบุคคลได้จากบุคคลที่มีอายุต่ำกว่า 14 ปีโดยเจตนา หากเราพบว่ามีการให้ข้อมูลดังกล่าว เราจะลบข้อมูลนั้นออกจากระบบของเราอย่างถาวรทันที

ความปลอดภัยของข้อมูล
เราใช้มาตรการรักษาความปลอดภัยที่เป็นมาตรฐานอุตสาหกรรมและเป็นที่ยอมรับในเชิงพาณิชย์ รวมถึงความปลอดภัยระดับแถว (RLS) และการเข้ารหัส เพื่อปกป้องข้อมูลที่ไม่ระบุตัวตนที่จัดการโดยโครงสร้างพื้นฐานของเรา อย่างไรก็ตาม ไม่มีวิธีการจัดเก็บข้อมูลทางอิเล็กทรอนิกส์หรือการส่งข้อมูลทางอินเทอร์เน็ตใดที่ปลอดภัย 100% และเราไม่สามารถรับประกันความปลอดภัยได้อย่างสมบูรณ์แบบ

การเปลี่ยนแปลงและการติดต่อ
เราขอสงวนสิทธิ์ในการอัปเดตนโยบายความเป็นส่วนตัวนี้ได้ตลอดเวลา การเปลี่ยนแปลงจะถูกโพสต์ในหน้านี้พร้อมกับวันที่ "อัปเดตล่าสุด" หากมีข้อสงสัยเกี่ยวกับความเป็นส่วนตัว โปรดติดต่อเจ้าหน้าที่ฝ่ายคุ้มครองข้อมูลส่วนบุคคลของเราที่ primenode.corp@gmail.com
