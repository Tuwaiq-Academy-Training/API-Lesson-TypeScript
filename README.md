# API-Lesson-TypeScript

# API

## سوف نتعلم في هذا الدرس :


- التعامل مع عمليات  CRUD 

ـــــــــــــــــــــــــــ



## ماهو API ؟

يعتبر  API مفهوم على  application programming interface 

واجهات برمجة التطبيقات هي أجزاء صغيرة من التعليمات البرمجية التي تجعل من الممكن للأجهزة الرقمية وتطبيقات البرامج وخوادم البيانات التحدث مع بعضها البعض ، وهي العمود الفقري الأساسي للعديد من الخدمات التي نعتمد عليها الآن.

البحث بشكل أعمق ، طريقة سهلة لفهم تعريف واجهة برمجة التطبيقات هي التفكير في التطبيقات التي تستخدمها كل يوم. في عالم متصل بالإنترنت ، تم تصميم تطبيقات الويب والهاتف المحمول ليستخدمها البشر ، بينما تم تصميم واجهات برمجة التطبيقات للأنظمة والتطبيقات الرقمية الأخرى لاستخدامها. تقوم كل من مواقع الويب وواجهات برمجة التطبيقات بنفس الأشياء ، مثل إرجاع البيانات والمحتوى والصور والفيديو والمعلومات الأخرى. لكن واجهات برمجة التطبيقات لا تعرض جميع التفاصيل اللازمة لجعل الأشياء تبدو جميلة للعين البشرية - فأنت تحصل فقط على البيانات الأولية وغيرها من المعلومات التي يمكن للآلة قراءتها والمطلوبة خلف الكواليس لتشغيل الموارد التي يتم تسليمها ، مع القليل جدًا مساعدة من الإنسان.


## ماهو API integration ؟

تكامل واجهة برمجة التطبيقات" هو مصطلح شائع جدًا في بحث Google ، السبب الكامل لوجود واجهات برمجة التطبيقات هو دعم التكامل. تكامل API هو ببساطة الاتصال بين اثنين (أو أكثر) من التطبيقات أو البرامج أو الخدمات أو الأنظمة باستخدام واجهات برمجة التطبيقات. تستخدم التطبيقات واجهات برمجة التطبيقات لإرسال واستقبال البيانات والمحتوى بين بعضها البعض


## تاريخ API

بدأت واجهات برمجة تطبيقات الويب بدايتها بوضع "commercial" في ".com" ، مما يعزز الشركات الناشئة التجارية التي تتطلع إلى تغيير الطريقة التي نؤدي بها أعمالنا على الويب. لقد استفادوا من هذه الوسيلة الجديدة لإتاحة المنتجات والخدمات للعملاء عبر موقع ويب واحد ، وأثناء عملهم مع الشركاء ، سعوا إلى أتمتة الكثير من التجارة التي كانت تدعم الويب وتضمنت عمالقة مثل Salesforce و eBay و Amazon . في عام 2004 ، بدأ التحول في مشهد واجهة برمجة التطبيقات بالظهور عندما بدأ ظهور سلالة جديدة من مزودي واجهة برمجة التطبيقات ، مما يوفر طرقًا لمشاركة المعلومات مع الشبكات الاجتماعية المحلية والعالمية ، بقيادة أمثال فيسبوك وتويتر. مع بداية قوية في التطبيقات التجارية والاجتماعية ، استمرت واجهات برمجة التطبيقات في النمو حيث انتقل كل شيء إلى السحابة ، وأصبحت أكثر قدرة على التنقل ، ووفرت الأساس لأجهزة الجيل التالي


## لماذا يتم استخدام API ؟


- تعمل واجهات برمجة التطبيقات على تشغيل تطبيقات سطح المكتب.
- واجهات برمجة التطبيقات وراء معظم تطبيقات الويب.
- تجعل واجهات برمجة التطبيقات تطبيقات الهاتف المحمول ممكنة.
- واجهات برمجة التطبيقات هي عمليات تكامل لحلول بدون رمز.
- تقوم واجهات برمجة التطبيقات بتوصيل الأجهزة بالإنترنت.
- تحدد واجهات برمجة التطبيقات الشبكات - أو المعلومات التي يتم تمريرها بين التطبيقات والأنظمة والأجهزة.

حتى أن واجهات برمجة التطبيقات تربط الأشياء اليومية مثل السيارات وأجراس الأبواب وغسالات الصحون والأجهزة القابلة للارتداء.


## كيف يعمل API ؟

تعمل واجهات برمجة التطبيقات من خلال مشاركة البيانات والمعلومات بين التطبيقات والأنظمة والأجهزة - مما يجعل من الممكن لهذه الأشياء التحدث مع بعضها البعض.

أحيانًا تكون أسهل طريقة للتفكير في واجهات برمجة التطبيقات هي التفكير في استعارة ، والسيناريو الشائع الذي يستخدمه الكثير من الناس هو العميل والنادل ومطبخ المطعم: يتحدث العميل إلى النادل ويخبر النادل بماذا هي تريد. ينزل النادل الطلب ويوصله إلى المطبخ. يقوم المطبخ بعملهم ، ويصنع الطعام ، ثم يقوم النادل بتسليم الطلب إلى العميل مرة أخرى.

في هذه الاستعارة ، الزبون مثل المستخدم الذي يخبر النادل بما يريد. النادل مثل واجهة برمجة التطبيقات ، يتلقى طلب العميل ويترجم الطلب إلى تعليمات سهلة المتابعة يستخدمها المطبخ بعد ذلك للوفاء بهذا الطلب - غالبًا باتباع مجموعة محددة من الرموز ، أو المدخلات ، التي يتعرف عليها المطبخ بسهولة. المطبخ مثل الخادم الذي يقوم بعمل الطلب بالطريقة التي يريدها العميل ، نأمل! عندما يكون الطعام جاهزًا ، يقوم النادل باستلام الطلب وتسليمه إلى العميل.


ماهي عمليات CRUD ؟ 
يرمز هذا الإختصار الى CREATE , READ , UPDATE , DELETE

وهي العمليات التي نقوم بالإستفاده منها عند استخدام API 

في حال اردنا استخدام API خارجي او قادم من server فلدينا اربع نقاط نستطيع التعام معها فيها .

في حال اردنا جلب البيانات وعرضها فقط فإننا نستخدم (.get) 
في حال اردنا اضافة بيانات على API فإننا نستخدم (.post)
في حال اردنا التعديل على إحدي البيانات فإننا نستخدم (.put)
في حال أردنا حذف بعض البيانات فإننا نستخدم (.delete)


## مثال :
    import React, { useEffect, useState } from "react";
    import { Link } from "react-router-dom"; 
    type ApiProps = {
      id: any;
      title: string;
      body?: string;
      userId?: number;
    };
    export const Get = () => {
      const [get, setGet] = useState<ApiProps[]>([]);
      useEffect(() => {
        try {
          // declare the data fetching
          const fetchData = async () => {
            const data = await fetch(
              "https://62d3e34acd960e45d44f7ccf.mockapi.io/task/",
              {
                method: "GET",
              }
            );
            const getData = await data.json();
            setGet(getData);
            console.log(getData);
          };
          // call the function
          fetchData();
        } catch (err) {
          // make sure to catch any error
          console.log("====================================");
          console.log(err);
          console.log("====================================");
        }
      }, []);
      const deleteTask = async (id: number) => {
        try {
          // find index of todo from id
          const data = await fetch(
            `https://62d3e34acd960e45d44f7ccf.mockapi.io/task/${id}`,
            {
              method: "DELETE",
            }
          );
          const getData = await data.json();
          setGet(
            getData.filter((tasks: any) => {
              return <>{tasks.id !== id}</>;
            })
          );
        } catch (err) {
          console.log("====================================");
          console.log(err);
          console.log("====================================");
        }
      };
      return (
        <div>
          <ol>
            {get.map((post, index) => {
              return (
                <div className="container" key={index}>
                  <li>
                    {post.title}
                    {/* {post.body}
                    {post.userId} */}
                    <Link to="/Ubdate">
                      <button onClick={() => localStorage.setItem("id", post.id)}>
                        Update
                      </button>
                    </Link>
                    <button
                      onClick={() => {
                        deleteTask(post.id);
                      }}
                    >
                      Delet
                    </button>
                  </li>
                </div>
              );
            })}
          </ol>
        </div>
      );
    };
    


لقد استخدما get&delete لجلب البيانات ومن ثم حذف اي نص لا نحتاج إليه  

