<Type Name="MethodDispatcherBaseWithSerializer" FullName="Microsoft.ServiceFabric.Services.Remoting.V1.Builder.MethodDispatcherBaseWithSerializer">
  <TypeSignature Language="C#" Value="public abstract class MethodDispatcherBaseWithSerializer : Microsoft.ServiceFabric.Services.Remoting.Builder.MethodDispatcherBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit MethodDispatcherBaseWithSerializer extends Microsoft.ServiceFabric.Services.Remoting.Builder.MethodDispatcherBase" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.V1.Builder.MethodDispatcherBaseWithSerializer" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class MethodDispatcherBaseWithSerializer&#xA;Inherits MethodDispatcherBase" />
  <TypeSignature Language="F#" Value="type MethodDispatcherBaseWithSerializer = class&#xA;    inherit MethodDispatcherBase" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.ServiceFabric.Services.Remoting.Builder.MethodDispatcherBase</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6b885-101">Die Klasse leitet die Anforderungen vom Client an die Schnittstellenmethode von prozessübergreifendes Objectts.</span><span class="sxs-lookup"><span data-stu-id="6b885-101">The class dispatches the requests from the client to the interface/method of the remoted objectts.</span></span>
            <span data-ttu-id="6b885-102">Diese Klasse wird vom Code-Generator Remoting verwendet.</span><span class="sxs-lookup"><span data-stu-id="6b885-102">This class is used by remoting code generator.</span></span> <span data-ttu-id="6b885-103">Diese Klasse wird das Serialisierungsprogramm zwischengespeichert.</span><span class="sxs-lookup"><span data-stu-id="6b885-103">This class caches the Serializer.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected MethodDispatcherBaseWithSerializer ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Builder.MethodDispatcherBaseWithSerializer.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinueWithResult&lt;TRetval&gt;">
      <MemberSignature Language="C#" Value="protected System.Threading.Tasks.Task&lt;object&gt; ContinueWithResult&lt;TRetval&gt; (int methodId, System.Threading.Tasks.Task&lt;TRetval&gt; task);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Threading.Tasks.Task`1&lt;object&gt; ContinueWithResult&lt;TRetval&gt;(int32 methodId, class System.Threading.Tasks.Task`1&lt;!!TRetval&gt; task) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Builder.MethodDispatcherBaseWithSerializer.ContinueWithResult``1(System.Int32,System.Threading.Tasks.Task{``0})" />
      <MemberSignature Language="VB.NET" Value="Protected Function ContinueWithResult(Of TRetval) (methodId As Integer, task As Task(Of TRetval)) As Task(Of Object)" />
      <MemberSignature Language="F#" Value="member this.ContinueWithResult : int * System.Threading.Tasks.Task&lt;'Retval&gt; -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="methodDispatcherBaseWithSerializer.ContinueWithResult (methodId, task)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TRetval" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="task" Type="System.Threading.Tasks.Task&lt;TRetval&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TRetval"><span data-ttu-id="6b885-104">Rückgabewert</span><span class="sxs-lookup"><span data-stu-id="6b885-104">Return value</span></span></typeparam>
        <param name="methodId"><span data-ttu-id="6b885-105">Methode-id</span><span class="sxs-lookup"><span data-stu-id="6b885-105">method id</span></span></param>
        <param name="task"><span data-ttu-id="6b885-106">Fortsetzungsaufgabe</span><span class="sxs-lookup"><span data-stu-id="6b885-106">continuation task</span></span></param>
        <summary>
            <span data-ttu-id="6b885-107">Intern – von Webdiensten verwendet</span><span class="sxs-lookup"><span data-stu-id="6b885-107">Internal - used by Service remoting</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6b885-108">Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="6b885-108">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateResponseBody">
      <MemberSignature Language="C#" Value="protected abstract object CreateResponseBody (int methodId, object retval);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance object CreateResponseBody(int32 methodId, object retval) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Builder.MethodDispatcherBaseWithSerializer.CreateResponseBody(System.Int32,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function CreateResponseBody (methodId As Integer, retval As Object) As Object" />
      <MemberSignature Language="F#" Value="abstract member CreateResponseBody : int * obj -&gt; obj" Usage="methodDispatcherBaseWithSerializer.CreateResponseBody (methodId, retval)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="retval" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="methodId"><span data-ttu-id="6b885-109">Die ID der Methode.</span><span class="sxs-lookup"><span data-stu-id="6b885-109">Id of the method.</span></span></param>
        <param name="retval"><span data-ttu-id="6b885-110">Der Rückgabewert der Methode.</span><span class="sxs-lookup"><span data-stu-id="6b885-110">The returned value from the method.</span></span></param>
        <summary>
            <span data-ttu-id="6b885-111">Diese Methode wird vom Verteiler für die generierte Methode zum Erstellen der Antwort aus dem angegebenen Rückgabewert als Ergebnis verteilen die Methode, die das Remoteobjekt implementiert.</span><span class="sxs-lookup"><span data-stu-id="6b885-111">This method is implemented by the generated method dispatcher to create the response from the specified return value as a result of dispatching the method to the remoted object.</span></span> 
            </summary>
        <returns><span data-ttu-id="6b885-112">Ein <see cref="T:System.Object">Objekt</see> , die den Antworttext zurück an den Client gesendet werden darstellt.</span><span class="sxs-lookup"><span data-stu-id="6b885-112">A <see cref="T:System.Object">Object</see> that represents the response body to be sent back to the client.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispatch">
      <MemberSignature Language="C#" Value="public override void Dispatch (object objectImplementation, int methodId, object messageBody);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance void Dispatch(object objectImplementation, int32 methodId, object messageBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Builder.MethodDispatcherBaseWithSerializer.Dispatch(System.Object,System.Int32,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Sub Dispatch (objectImplementation As Object, methodId As Integer, messageBody As Object)" />
      <MemberSignature Language="F#" Value="override this.Dispatch : obj * int * obj -&gt; unit" Usage="methodDispatcherBaseWithSerializer.Dispatch (objectImplementation, methodId, messageBody)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="objectImplementation" Type="System.Object" />
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="messageBody" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="objectImplementation"></param>
        <param name="methodId"></param>
        <param name="messageBody"></param>
        <summary>
            <span data-ttu-id="6b885-113">Diese Methode wird verwendet, eine unidirektionale Nachrichten auf der angegebenen MethodId der Schnittstelle implementiert, die vom Remote-Objekt verteilt wird.</span><span class="sxs-lookup"><span data-stu-id="6b885-113">This method is used to dispatch one way messages to the specified methodId of the interface implemented by the remoted object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DispatchAsync">
      <MemberSignature Language="C#" Value="public override System.Threading.Tasks.Task&lt;object&gt; DispatchAsync (object objectImplementation, int methodId, object requestBody, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance class System.Threading.Tasks.Task`1&lt;object&gt; DispatchAsync(object objectImplementation, int32 methodId, object requestBody, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Builder.MethodDispatcherBaseWithSerializer.DispatchAsync(System.Object,System.Int32,System.Object,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="override this.DispatchAsync : obj * int * obj * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="methodDispatcherBaseWithSerializer.DispatchAsync (objectImplementation, methodId, requestBody, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="objectImplementation" Type="System.Object" />
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="requestBody" Type="System.Object" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="objectImplementation"></param>
        <param name="methodId"></param>
        <param name="requestBody"></param>
        <param name="cancellationToken"></param>
        <summary>
            <span data-ttu-id="6b885-114">Diese Methode wird verwendet, um dispatch-Anforderung zur angegebenen MethodId der Schnittstelle implementiert, die vom Remote-Objekt.</span><span class="sxs-lookup"><span data-stu-id="6b885-114">This method is used to dispatch request to the specified methodId of the interface implemented by the remoted object.</span></span>
             </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDispatch">
      <MemberSignature Language="C#" Value="protected abstract void OnDispatch (int methodId, object remotedObject, object messageBody);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void OnDispatch(int32 methodId, object remotedObject, object messageBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Builder.MethodDispatcherBaseWithSerializer.OnDispatch(System.Int32,System.Object,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Sub OnDispatch (methodId As Integer, remotedObject As Object, messageBody As Object)" />
      <MemberSignature Language="F#" Value="abstract member OnDispatch : int * obj * obj -&gt; unit" Usage="methodDispatcherBaseWithSerializer.OnDispatch (methodId, remotedObject, messageBody)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="remotedObject" Type="System.Object" />
        <Parameter Name="messageBody" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="methodId"><span data-ttu-id="6b885-115">Die ID der Methode.</span><span class="sxs-lookup"><span data-stu-id="6b885-115">Id of the method.</span></span></param>
        <param name="remotedObject"><span data-ttu-id="6b885-116">Die Instanz prozessübergreifendes Remoteobjekt.</span><span class="sxs-lookup"><span data-stu-id="6b885-116">The remoted object instance.</span></span></param>
        <param name="messageBody"><span data-ttu-id="6b885-117">Nachrichtentext</span><span class="sxs-lookup"><span data-stu-id="6b885-117">message body</span></span></param>
        <summary>
            <span data-ttu-id="6b885-118">Diese Methode wird vom Verteiler für die generierte Methode beim Verteilen von unidirektionaler Nachrichten an der angegebenen MethodId der Schnittstelle implementiert, die vom Remote-Objekt implementiert.</span><span class="sxs-lookup"><span data-stu-id="6b885-118">This method is implemented by the generated method dispatcher to dispatch one way messages to the specified methodId of the interface implemented by the remoted object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OnDispatchAsync">
      <MemberSignature Language="C#" Value="protected abstract System.Threading.Tasks.Task&lt;object&gt; OnDispatchAsync (int methodId, object remotedObject, object requestBody, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;object&gt; OnDispatchAsync(int32 methodId, object remotedObject, object requestBody, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.V1.Builder.MethodDispatcherBaseWithSerializer.OnDispatchAsync(System.Int32,System.Object,System.Object,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member OnDispatchAsync : int * obj * obj * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="methodDispatcherBaseWithSerializer.OnDispatchAsync (methodId, remotedObject, requestBody, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="remotedObject" Type="System.Object" />
        <Parameter Name="requestBody" Type="System.Object" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="methodId"><span data-ttu-id="6b885-119">Die ID der Methode.</span><span class="sxs-lookup"><span data-stu-id="6b885-119">Id of the method.</span></span></param>
        <param name="remotedObject"><span data-ttu-id="6b885-120">Die Instanz prozessübergreifendes Remoteobjekt.</span><span class="sxs-lookup"><span data-stu-id="6b885-120">The remoted object instance.</span></span></param>
        <param name="requestBody"><span data-ttu-id="6b885-121">Anforderungstext</span><span class="sxs-lookup"><span data-stu-id="6b885-121">Request body</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="6b885-122">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="6b885-122">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="6b885-123">Diese Methode wird vom Verteiler für die generierte Methode auf dispatch-Anforderung zur angegebenen MethodId der durch das Remoteobjekt implementierten Schnittstelle implementiert.</span><span class="sxs-lookup"><span data-stu-id="6b885-123">This method is implemented by the generated method dispatcher to dispatch request to the specified methodId of the interface implemented by the remoted object.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="6b885-124">Ein <see cref="T:System.Threading.Tasks.Task">Aufgabe</see> , ausstehenden Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="6b885-124">A <see cref="T:System.Threading.Tasks.Task">Task</see> that represents outstanding operation.</span></span> <span data-ttu-id="6b885-125">Das Ergebnis des Vorgangs ist der Rückgabewert der Methode.</span><span class="sxs-lookup"><span data-stu-id="6b885-125">The result of the task is the return value from the method.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>