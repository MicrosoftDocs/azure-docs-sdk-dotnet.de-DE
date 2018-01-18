<Type Name="ProxyBase" FullName="Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase">
  <TypeSignature Language="C#" Value="public abstract class ProxyBase" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit ProxyBase extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class ProxyBase" />
  <TypeSignature Language="F#" Value="type ProxyBase = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="45f79-101">Die Basisklasse, die von Remoting-Code-Generator verwendet, um den Proxy für die Remote-Schnittstellen zu generieren.</span><span class="sxs-lookup"><span data-stu-id="45f79-101">The base class used by remoting code generator to generate the proxy for the remoted interfaces.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected ProxyBase ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="45f79-102">Initialisiert eine neue Instanz der ProxyBase-Klasse.</span><span class="sxs-lookup"><span data-stu-id="45f79-102">Initializes a new instance of the ProxyBase class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinueWith">
      <MemberSignature Language="C#" Value="protected System.Threading.Tasks.Task ContinueWith (System.Threading.Tasks.Task&lt;object&gt; task);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Threading.Tasks.Task ContinueWith(class System.Threading.Tasks.Task`1&lt;object&gt; task) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase.ContinueWith(System.Threading.Tasks.Task{System.Object})" />
      <MemberSignature Language="F#" Value="member this.ContinueWith : System.Threading.Tasks.Task&lt;obj&gt; -&gt; System.Threading.Tasks.Task" Usage="proxyBase.ContinueWith task" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase/&lt;ContinueWith&gt;d__12))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="task" Type="System.Threading.Tasks.Task&lt;System.Object&gt;" />
      </Parameters>
      <Docs>
        <param name="task"><span data-ttu-id="45f79-103">Eine Aufgabe, die den asynchronen Vorgang für den remote-Methodenaufruf darstellt.</span><span class="sxs-lookup"><span data-stu-id="45f79-103">A task that represents the asynchronous operation for remote method call.</span></span></param>
        <summary>
            <span data-ttu-id="45f79-104">Wird aufgerufen, durch die generierte Proxyklasse, um den Vorgang fortzusetzen, nach dem Abrufen des Antworttexts, die keinen Wert verfügt.</span><span class="sxs-lookup"><span data-stu-id="45f79-104">Called by the generated proxy class to continue after getting the response body that does not have value.</span></span>
            </summary>
        <returns><span data-ttu-id="45f79-105">Eine Aufgabe, die den asynchronen Vorgang für den remote-Methodenaufruf darstellt.</span><span class="sxs-lookup"><span data-stu-id="45f79-105">A task that represents the asynchronous operation for remote method call.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinueWithResult&lt;TRetval&gt;">
      <MemberSignature Language="C#" Value="protected System.Threading.Tasks.Task&lt;TRetval&gt; ContinueWithResult&lt;TRetval&gt; (int interfaceId, int methodId, System.Threading.Tasks.Task&lt;object&gt; task);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Threading.Tasks.Task`1&lt;!!TRetval&gt; ContinueWithResult&lt;TRetval&gt;(int32 interfaceId, int32 methodId, class System.Threading.Tasks.Task`1&lt;object&gt; task) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase.ContinueWithResult``1(System.Int32,System.Int32,System.Threading.Tasks.Task{System.Object})" />
      <MemberSignature Language="VB.NET" Value="Protected Function ContinueWithResult(Of TRetval) (interfaceId As Integer, methodId As Integer, task As Task(Of Object)) As Task(Of TRetval)" />
      <MemberSignature Language="F#" Value="member this.ContinueWithResult : int * int * System.Threading.Tasks.Task&lt;obj&gt; -&gt; System.Threading.Tasks.Task&lt;'Retval&gt;" Usage="proxyBase.ContinueWithResult (interfaceId, methodId, task)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase/&lt;ContinueWithResult&gt;d__4`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TRetval&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TRetval" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="interfaceId" Type="System.Int32" />
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="task" Type="System.Threading.Tasks.Task&lt;System.Object&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TRetval">
          <span data-ttu-id="45f79-106"><see cref="T:System.Type" />der remote-Methode der Rückgabewert.</span><span class="sxs-lookup"><span data-stu-id="45f79-106"><see cref="T:System.Type" /> of the remote method return value.</span></span></typeparam>
        <param name="interfaceId"><span data-ttu-id="45f79-107">Schnittstellen-Id für die Remote-Schnittstelle.</span><span class="sxs-lookup"><span data-stu-id="45f79-107">Interface Id for the remoted interface.</span></span></param>
        <param name="methodId"><span data-ttu-id="45f79-108">Methode-Id für die remote-Methode.</span><span class="sxs-lookup"><span data-stu-id="45f79-108">Method Id for the remote method.</span></span></param>
        <param name="task"><span data-ttu-id="45f79-109">Eine Aufgabe, die den asynchronen Vorgang für den remote-Methodenaufruf darstellt.</span><span class="sxs-lookup"><span data-stu-id="45f79-109">A task that represents the asynchronous operation for remote method call.</span></span></param>
        <summary>
            <span data-ttu-id="45f79-110">Wird aufgerufen, durch die generierte Proxyklasse, um das Ergebnis aus dem Antworttext abzurufen.</span><span class="sxs-lookup"><span data-stu-id="45f79-110">Called by the generated proxy class to get the result from the response body.</span></span>
            </summary>
        <returns><span data-ttu-id="45f79-111">Eine Aufgabe, die den asynchronen Vorgang für den remote-Methodenaufruf darstellt.</span><span class="sxs-lookup"><span data-stu-id="45f79-111">A task that represents the asynchronous operation for remote method call.</span></span>
            <span data-ttu-id="45f79-112">Der Wert von der TRetval enthält den Rückgabewert der remote-Methode.</span><span class="sxs-lookup"><span data-stu-id="45f79-112">The value of the TRetval contains the remote method return value.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContinueWithResultV2&lt;TRetval&gt;">
      <MemberSignature Language="C#" Value="protected System.Threading.Tasks.Task&lt;TRetval&gt; ContinueWithResultV2&lt;TRetval&gt; (System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt; task);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Threading.Tasks.Task`1&lt;!!TRetval&gt; ContinueWithResultV2&lt;TRetval&gt;(class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt; task) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase.ContinueWithResultV2``1(System.Threading.Tasks.Task{Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody})" />
      <MemberSignature Language="VB.NET" Value="Protected Function ContinueWithResultV2(Of TRetval) (task As Task(Of IServiceRemotingResponseMessageBody)) As Task(Of TRetval)" />
      <MemberSignature Language="F#" Value="member this.ContinueWithResultV2 : System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt; -&gt; System.Threading.Tasks.Task&lt;'Retval&gt;" Usage="proxyBase.ContinueWithResultV2 task" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase/&lt;ContinueWithResultV2&gt;d__15`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TRetval&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TRetval" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="task" Type="System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt;" />
      </Parameters>
      <Docs>
        <typeparam name="TRetval">
          <span data-ttu-id="45f79-113"><see cref="T:System.Type" />der remote-Methode der Rückgabewert.</span><span class="sxs-lookup"><span data-stu-id="45f79-113"><see cref="T:System.Type" /> of the remote method return value.</span></span></typeparam>
        <param name="task"><span data-ttu-id="45f79-114">Eine Aufgabe, die den asynchronen Vorgang für den remote-Methodenaufruf darstellt.</span><span class="sxs-lookup"><span data-stu-id="45f79-114">A task that represents the asynchronous operation for remote method call.</span></span></param>
        <summary>
            <span data-ttu-id="45f79-115">Wird aufgerufen, durch die generierte Proxyklasse, um das Ergebnis aus dem Antworttext abzurufen.</span><span class="sxs-lookup"><span data-stu-id="45f79-115">Called by the generated proxy class to get the result from the response body.</span></span>
            </summary>
        <returns><span data-ttu-id="45f79-116">Eine Aufgabe, die den asynchronen Vorgang für den remote-Methodenaufruf darstellt.</span><span class="sxs-lookup"><span data-stu-id="45f79-116">A task that represents the asynchronous operation for remote method call.</span></span>
            <span data-ttu-id="45f79-117">Der Wert von der TRetval enthält den Rückgabewert der remote-Methode.</span><span class="sxs-lookup"><span data-stu-id="45f79-117">The value of the TRetval contains the remote method return value.</span></span> </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateRequestMessageBodyV2">
      <MemberSignature Language="C#" Value="protected virtual Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody CreateRequestMessageBodyV2 (string interfaceName, string methodName, int parameterCount);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody CreateRequestMessageBodyV2(string interfaceName, string methodName, int32 parameterCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase.CreateRequestMessageBodyV2(System.String,System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Function CreateRequestMessageBodyV2 (interfaceName As String, methodName As String, parameterCount As Integer) As IServiceRemotingRequestMessageBody" />
      <MemberSignature Language="F#" Value="abstract member CreateRequestMessageBodyV2 : string * string * int -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody&#xA;override this.CreateRequestMessageBodyV2 : string * string * int -&gt; Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody" Usage="proxyBase.CreateRequestMessageBodyV2 (interfaceName, methodName, parameterCount)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="interfaceName" Type="System.String" />
        <Parameter Name="methodName" Type="System.String" />
        <Parameter Name="parameterCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="interfaceName"><span data-ttu-id="45f79-118">Vollständigen Namen der Dienstschnittstelle diesem Aufruf</span><span class="sxs-lookup"><span data-stu-id="45f79-118">Full Name of the service interface for which this call is invoked</span></span></param>
        <param name="methodName"><span data-ttu-id="45f79-119">Der Methodenname der Dienstschnittstelle diesem Aufruf</span><span class="sxs-lookup"><span data-stu-id="45f79-119">Method Name of the service interface for which this call is invoked</span></span></param>
        <param name="parameterCount"><span data-ttu-id="45f79-120">Anzahl von Parametern im Dienst-Schnittstellenmethode</span><span class="sxs-lookup"><span data-stu-id="45f79-120">Number of Parameters in the service interface Method</span></span></param>
        <summary>
            <span data-ttu-id="45f79-121">Erstellt die Anforderungsnachricht Remoting Text</span><span class="sxs-lookup"><span data-stu-id="45f79-121">Creates the Remoting request message Body</span></span> 
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetReturnValue">
      <MemberSignature Language="C#" Value="protected abstract object GetReturnValue (int interfaceId, int methodId, object responseBody);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance object GetReturnValue(int32 interfaceId, int32 methodId, object responseBody) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase.GetReturnValue(System.Int32,System.Int32,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected MustOverride Function GetReturnValue (interfaceId As Integer, methodId As Integer, responseBody As Object) As Object" />
      <MemberSignature Language="F#" Value="abstract member GetReturnValue : int * int * obj -&gt; obj" Usage="proxyBase.GetReturnValue (interfaceId, methodId, responseBody)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Object</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="interfaceId" Type="System.Int32" />
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="responseBody" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="interfaceId"><span data-ttu-id="45f79-122">Schnittstellen-Id für die Akteur-Schnittstelle.</span><span class="sxs-lookup"><span data-stu-id="45f79-122">Interface Id for the actor interface.</span></span></param>
        <param name="methodId"><span data-ttu-id="45f79-123">Methode-Id für die Akteur-Methode.</span><span class="sxs-lookup"><span data-stu-id="45f79-123">Method Id for the actor method.</span></span></param>
        <param name="responseBody"><span data-ttu-id="45f79-124">Der Antworttext.</span><span class="sxs-lookup"><span data-stu-id="45f79-124">Response body.</span></span></param>
        <summary>
            <span data-ttu-id="45f79-125">Geben Sie die Umwandlung der Antworttext und extrahiert den Wert aus der abgeleiteten Klasse implementiert.</span><span class="sxs-lookup"><span data-stu-id="45f79-125">Implemented by the derived class to type cast the response body and extract the value from it.</span></span>
            </summary>
        <returns><span data-ttu-id="45f79-126">Der Rückgabewert des Methodenaufrufs als <see cref="T:System.Object" />.</span><span class="sxs-lookup"><span data-stu-id="45f79-126">Return value of method call as <see cref="T:System.Object" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Invoke">
      <MemberSignature Language="C#" Value="protected void Invoke (int interfaceId, int methodId, object requestMsgBodyValue);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void Invoke(int32 interfaceId, int32 methodId, object requestMsgBodyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase.Invoke(System.Int32,System.Int32,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub Invoke (interfaceId As Integer, methodId As Integer, requestMsgBodyValue As Object)" />
      <MemberSignature Language="F#" Value="member this.Invoke : int * int * obj -&gt; unit" Usage="proxyBase.Invoke (interfaceId, methodId, requestMsgBodyValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="interfaceId" Type="System.Int32" />
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="requestMsgBodyValue" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="interfaceId"><span data-ttu-id="45f79-127">Die ID der remote-Schnittstelle.</span><span class="sxs-lookup"><span data-stu-id="45f79-127">Id of the remote interface.</span></span></param>
        <param name="methodId"><span data-ttu-id="45f79-128">ID der remote-Methode Invokved sein.</span><span class="sxs-lookup"><span data-stu-id="45f79-128">Id of the remote method to be invokved.</span></span></param>
        <param name="requestMsgBodyValue"><span data-ttu-id="45f79-129">Der Nachrichtentext Remoteobjekt gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="45f79-129">Message body to be sent to remote object.</span></span></param>
        <summary>
            <span data-ttu-id="45f79-130">Wird von der generierten Proxyklasse zum Senden der Nachricht auf das Remoteobjekt aufgerufen.</span><span class="sxs-lookup"><span data-stu-id="45f79-130">Called by the generated proxy class to send the message to the remote object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeAsync">
      <MemberSignature Language="C#" Value="protected System.Threading.Tasks.Task&lt;object&gt; InvokeAsync (int interfaceId, int methodId, object requestMsgBodyValue, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Threading.Tasks.Task`1&lt;object&gt; InvokeAsync(int32 interfaceId, int32 methodId, object requestMsgBodyValue, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase.InvokeAsync(System.Int32,System.Int32,System.Object,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.InvokeAsync : int * int * obj * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;obj&gt;" Usage="proxyBase.InvokeAsync (interfaceId, methodId, requestMsgBodyValue, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase/&lt;InvokeAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Object&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="interfaceId" Type="System.Int32" />
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="requestMsgBodyValue" Type="System.Object" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="interfaceId"><span data-ttu-id="45f79-131">Die ID der remote-Schnittstelle.</span><span class="sxs-lookup"><span data-stu-id="45f79-131">Id of the remote interface.</span></span></param>
        <param name="methodId"><span data-ttu-id="45f79-132">ID der remote-Methode Invokved sein.</span><span class="sxs-lookup"><span data-stu-id="45f79-132">Id of the remote method to be invokved.</span></span></param>
        <param name="requestMsgBodyValue"><span data-ttu-id="45f79-133">Der Anforderungstext.</span><span class="sxs-lookup"><span data-stu-id="45f79-133">Request body.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="45f79-134">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="45f79-134">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="45f79-135">Wird aufgerufen, von der generierten Proxyklasse zum Senden der Anforderung an das Remoteobjekt und rufen Sie die Antwort zurück.</span><span class="sxs-lookup"><span data-stu-id="45f79-135">Called by the generated proxy class to send the request to the remote object and get the response back.</span></span>
            </summary>
        <returns><span data-ttu-id="45f79-136">Remoteobjekt rufen Sie eine Aufgabe, die asynchron asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="45f79-136">A task that represents the asynchronous operation async call to remote object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeAsyncV2">
      <MemberSignature Language="C#" Value="protected System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt; InvokeAsyncV2 (int interfaceId, int methodId, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody requestMsgBodyValue, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt; InvokeAsyncV2(int32 interfaceId, int32 methodId, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody requestMsgBodyValue, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase.InvokeAsyncV2(System.Int32,System.Int32,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.InvokeAsyncV2 : int * int * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt;" Usage="proxyBase.InvokeAsyncV2 (interfaceId, methodId, requestMsgBodyValue, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase/&lt;InvokeAsyncV2&gt;d__16))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingResponseMessageBody&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="interfaceId" Type="System.Int32" />
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="requestMsgBodyValue" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="interfaceId"><span data-ttu-id="45f79-137">Die ID der remote-Schnittstelle.</span><span class="sxs-lookup"><span data-stu-id="45f79-137">Id of the remote interface.</span></span></param>
        <param name="methodId"><span data-ttu-id="45f79-138">ID der remote-Methode Invokved sein.</span><span class="sxs-lookup"><span data-stu-id="45f79-138">Id of the remote method to be invokved.</span></span></param>
        <param name="requestMsgBodyValue"><span data-ttu-id="45f79-139">Der Anforderungstext.</span><span class="sxs-lookup"><span data-stu-id="45f79-139">Request body.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="45f79-140">Abbruchtoken</span><span class="sxs-lookup"><span data-stu-id="45f79-140">Cancellation token</span></span></param>
        <summary>
            <span data-ttu-id="45f79-141">Wird aufgerufen, von der generierten Proxyklasse zum Senden der Anforderung an das Remoteobjekt und rufen Sie die Antwort zurück.</span><span class="sxs-lookup"><span data-stu-id="45f79-141">Called by the generated proxy class to send the request to the remote object and get the response back.</span></span>
            </summary>
        <returns><span data-ttu-id="45f79-142">Remoteobjekt rufen Sie eine Aufgabe, die asynchron asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="45f79-142">A task that represents the asynchronous operation async call to remote object.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InvokeV2">
      <MemberSignature Language="C#" Value="protected void InvokeV2 (int interfaceId, int methodId, Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody requestMsgBodyValue);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void InvokeV2(int32 interfaceId, int32 methodId, class Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody requestMsgBodyValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Services.Remoting.Builder.ProxyBase.InvokeV2(System.Int32,System.Int32,Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody)" />
      <MemberSignature Language="VB.NET" Value="Protected Sub InvokeV2 (interfaceId As Integer, methodId As Integer, requestMsgBodyValue As IServiceRemotingRequestMessageBody)" />
      <MemberSignature Language="F#" Value="member this.InvokeV2 : int * int * Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody -&gt; unit" Usage="proxyBase.InvokeV2 (interfaceId, methodId, requestMsgBodyValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Services.Remoting</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="interfaceId" Type="System.Int32" />
        <Parameter Name="methodId" Type="System.Int32" />
        <Parameter Name="requestMsgBodyValue" Type="Microsoft.ServiceFabric.Services.Remoting.V2.IServiceRemotingRequestMessageBody" />
      </Parameters>
      <Docs>
        <param name="interfaceId"><span data-ttu-id="45f79-143">Die ID der remote-Schnittstelle.</span><span class="sxs-lookup"><span data-stu-id="45f79-143">Id of the remote interface.</span></span></param>
        <param name="methodId"><span data-ttu-id="45f79-144">ID der remote-Methode Invokved sein.</span><span class="sxs-lookup"><span data-stu-id="45f79-144">Id of the remote method to be invokved.</span></span></param>
        <param name="requestMsgBodyValue"><span data-ttu-id="45f79-145">Der Nachrichtentext Remoteobjekt gesendet werden.</span><span class="sxs-lookup"><span data-stu-id="45f79-145">Message body to be sent to remote object.</span></span></param>
        <summary>
            <span data-ttu-id="45f79-146">Wird aufgerufen, von der generierten Proxyklasse Remoteobjekts der RequestMessage an.</span><span class="sxs-lookup"><span data-stu-id="45f79-146">Called by the generated proxy class to send the requestMessage to the remote object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>