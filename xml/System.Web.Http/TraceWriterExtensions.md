<Type Name="TraceWriterExtensions" FullName="System.Web.Http.TraceWriterExtensions">
  <TypeSignature Language="C#" Value="public static class TraceWriterExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit TraceWriterExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Web.Http.TraceWriterExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module TraceWriterExtensions" />
  <TypeSignature Language="F#" Value="type TraceWriterExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>System.ComponentModel.EditorBrowsable(System.ComponentModel.EditorBrowsableState.Never)</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="29c8b-101">Erweiterungsmethoden für <see cref="T:System.Web.Http.Tracing.ITraceWriter" /> leicht verwendbare Methoden für die Anmeldung bereitgestellt.</span><span class="sxs-lookup"><span data-stu-id="29c8b-101">Extension methods for <see cref="T:System.Web.Http.Tracing.ITraceWriter" /> providing easy usable methods for logging.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Debug">
      <MemberSignature Language="C#" Value="public static void Debug (this System.Web.Http.Tracing.ITraceWriter traceWriter, string message, System.Net.Http.HttpRequestMessage request = null, string category = &quot;&quot;);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Debug(class System.Web.Http.Tracing.ITraceWriter traceWriter, string message, class System.Net.Http.HttpRequestMessage request, string category) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Web.Http.TraceWriterExtensions.Debug(System.Web.Http.Tracing.ITraceWriter,System.String,System.Net.Http.HttpRequestMessage,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Debug (traceWriter As ITraceWriter, message As String, Optional request As HttpRequestMessage = null, Optional category As String = &quot;&quot;)" />
      <MemberSignature Language="F#" Value="static member Debug : System.Web.Http.Tracing.ITraceWriter * string * System.Net.Http.HttpRequestMessage * string -&gt; unit" Usage="System.Web.Http.TraceWriterExtensions.Debug (traceWriter, message, request, category)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1026:DefaultParametersShouldNotBeUsed", Justification="Default parameters are in order for log messages.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="traceWriter" Type="System.Web.Http.Tracing.ITraceWriter" RefType="this" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" />
        <Parameter Name="category" Type="System.String">
          <Attributes>
            <Attribute>
              <AttributeName>System.Runtime.CompilerServices.CallerMemberName</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="traceWriter"><span data-ttu-id="29c8b-102">Der <see cref="T:System.Web.Http.Tracing.ITraceWriter" /></span><span class="sxs-lookup"><span data-stu-id="29c8b-102">The <see cref="T:System.Web.Http.Tracing.ITraceWriter" /></span></span></param>
        <param name="message"><span data-ttu-id="29c8b-103">Die zu protokollierende Meldung.</span><span class="sxs-lookup"><span data-stu-id="29c8b-103">The message to log.</span></span></param>
        <param name="request"><span data-ttu-id="29c8b-104">Anforderung für die Nachrichtenkorrelation verwendet.</span><span class="sxs-lookup"><span data-stu-id="29c8b-104">Request used for message correlation.</span></span> <span data-ttu-id="29c8b-105">Der Standardwert ist null.</span><span class="sxs-lookup"><span data-stu-id="29c8b-105">Defaults to null.</span></span></param>
        <param name="category"><span data-ttu-id="29c8b-106">Die Kategorie für die Ablaufverfolgung.</span><span class="sxs-lookup"><span data-stu-id="29c8b-106">The category for the trace.</span></span> <span data-ttu-id="29c8b-107">Der Standardwert ist die Methode oder Eigenschaft den Namen des Aufrufers.</span><span class="sxs-lookup"><span data-stu-id="29c8b-107">Defaults to the method or property name of the caller.</span></span></param>
        <summary>
            <span data-ttu-id="29c8b-108">Schreibt eine <see cref="T:System.Web.Http.Tracing.TraceRecord" /> am <see cref="F:System.Web.Http.Tracing.TraceLevel.Debug" /> mit der angegebenen Meldung.</span><span class="sxs-lookup"><span data-stu-id="29c8b-108">Writes a <see cref="T:System.Web.Http.Tracing.TraceRecord" /> at <see cref="F:System.Web.Http.Tracing.TraceLevel.Debug" /> with the given message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public static void Error (this System.Web.Http.Tracing.ITraceWriter traceWriter, Exception exception, System.Net.Http.HttpRequestMessage request = null, string category = &quot;&quot;);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Error(class System.Web.Http.Tracing.ITraceWriter traceWriter, class System.Exception exception, class System.Net.Http.HttpRequestMessage request, string category) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Web.Http.TraceWriterExtensions.Error(System.Web.Http.Tracing.ITraceWriter,System.Exception,System.Net.Http.HttpRequestMessage,System.String)" />
      <MemberSignature Language="F#" Value="static member Error : System.Web.Http.Tracing.ITraceWriter * Exception * System.Net.Http.HttpRequestMessage * string -&gt; unit" Usage="System.Web.Http.TraceWriterExtensions.Error (traceWriter, exception, request, category)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1026:DefaultParametersShouldNotBeUsed", Justification="Default parameters are in order for log messages.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="traceWriter" Type="System.Web.Http.Tracing.ITraceWriter" RefType="this" />
        <Parameter Name="exception" Type="System.Exception" />
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" />
        <Parameter Name="category" Type="System.String">
          <Attributes>
            <Attribute>
              <AttributeName>System.Runtime.CompilerServices.CallerMemberName</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="traceWriter"><span data-ttu-id="29c8b-109">Der <see cref="T:System.Web.Http.Tracing.ITraceWriter" /></span><span class="sxs-lookup"><span data-stu-id="29c8b-109">The <see cref="T:System.Web.Http.Tracing.ITraceWriter" /></span></span></param>
        <param name="exception"><span data-ttu-id="29c8b-110">Die zu protokollierende Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="29c8b-110">The exception to log.</span></span></param>
        <param name="request"><span data-ttu-id="29c8b-111">Anforderung für die Nachrichtenkorrelation verwendet.</span><span class="sxs-lookup"><span data-stu-id="29c8b-111">Request used for message correlation.</span></span> <span data-ttu-id="29c8b-112">Der Standardwert ist null.</span><span class="sxs-lookup"><span data-stu-id="29c8b-112">Defaults to null.</span></span></param>
        <param name="category"><span data-ttu-id="29c8b-113">Die Kategorie für die Ablaufverfolgung.</span><span class="sxs-lookup"><span data-stu-id="29c8b-113">The category for the trace.</span></span> <span data-ttu-id="29c8b-114">Der Standardwert ist die Methode oder Eigenschaft den Namen des Aufrufers.</span><span class="sxs-lookup"><span data-stu-id="29c8b-114">Defaults to the method or property name of the caller.</span></span></param>
        <summary>
            <span data-ttu-id="29c8b-115">Schreibt eine <see cref="T:System.Web.Http.Tracing.TraceRecord" /> am <see cref="F:System.Web.Http.Tracing.TraceLevel.Error" /> mit der angegebenen <paramref name="exception" />.</span><span class="sxs-lookup"><span data-stu-id="29c8b-115">Writes a <see cref="T:System.Web.Http.Tracing.TraceRecord" /> at <see cref="F:System.Web.Http.Tracing.TraceLevel.Error" /> with the given <paramref name="exception" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public static void Error (this System.Web.Http.Tracing.ITraceWriter traceWriter, string message, System.Net.Http.HttpRequestMessage request = null, string category = &quot;&quot;);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Error(class System.Web.Http.Tracing.ITraceWriter traceWriter, string message, class System.Net.Http.HttpRequestMessage request, string category) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Web.Http.TraceWriterExtensions.Error(System.Web.Http.Tracing.ITraceWriter,System.String,System.Net.Http.HttpRequestMessage,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Error (traceWriter As ITraceWriter, message As String, Optional request As HttpRequestMessage = null, Optional category As String = &quot;&quot;)" />
      <MemberSignature Language="F#" Value="static member Error : System.Web.Http.Tracing.ITraceWriter * string * System.Net.Http.HttpRequestMessage * string -&gt; unit" Usage="System.Web.Http.TraceWriterExtensions.Error (traceWriter, message, request, category)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1026:DefaultParametersShouldNotBeUsed", Justification="Default parameters are in order for log messages.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="traceWriter" Type="System.Web.Http.Tracing.ITraceWriter" RefType="this" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" />
        <Parameter Name="category" Type="System.String">
          <Attributes>
            <Attribute>
              <AttributeName>System.Runtime.CompilerServices.CallerMemberName</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="traceWriter"><span data-ttu-id="29c8b-116">Der <see cref="T:System.Web.Http.Tracing.ITraceWriter" /></span><span class="sxs-lookup"><span data-stu-id="29c8b-116">The <see cref="T:System.Web.Http.Tracing.ITraceWriter" /></span></span></param>
        <param name="message"><span data-ttu-id="29c8b-117">Die zu protokollierende Meldung.</span><span class="sxs-lookup"><span data-stu-id="29c8b-117">The message to log.</span></span></param>
        <param name="request"><span data-ttu-id="29c8b-118">Anforderung für die Nachrichtenkorrelation verwendet.</span><span class="sxs-lookup"><span data-stu-id="29c8b-118">Request used for message correlation.</span></span> <span data-ttu-id="29c8b-119">Der Standardwert ist null.</span><span class="sxs-lookup"><span data-stu-id="29c8b-119">Defaults to null.</span></span></param>
        <param name="category"><span data-ttu-id="29c8b-120">Die Kategorie für die Ablaufverfolgung.</span><span class="sxs-lookup"><span data-stu-id="29c8b-120">The category for the trace.</span></span> <span data-ttu-id="29c8b-121">Der Standardwert ist die Methode oder Eigenschaft den Namen des Aufrufers.</span><span class="sxs-lookup"><span data-stu-id="29c8b-121">Defaults to the method or property name of the caller.</span></span></param>
        <summary>
            <span data-ttu-id="29c8b-122">Schreibt eine <see cref="T:System.Web.Http.Tracing.TraceRecord" /> am <see cref="F:System.Web.Http.Tracing.TraceLevel.Error" /> mit der angegebenen Meldung.</span><span class="sxs-lookup"><span data-stu-id="29c8b-122">Writes a <see cref="T:System.Web.Http.Tracing.TraceRecord" /> at <see cref="F:System.Web.Http.Tracing.TraceLevel.Error" /> with the given message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Error">
      <MemberSignature Language="C#" Value="public static void Error (this System.Web.Http.Tracing.ITraceWriter traceWriter, string message, Exception exception, System.Net.Http.HttpRequestMessage request = null, string category = &quot;&quot;);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Error(class System.Web.Http.Tracing.ITraceWriter traceWriter, string message, class System.Exception exception, class System.Net.Http.HttpRequestMessage request, string category) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Web.Http.TraceWriterExtensions.Error(System.Web.Http.Tracing.ITraceWriter,System.String,System.Exception,System.Net.Http.HttpRequestMessage,System.String)" />
      <MemberSignature Language="F#" Value="static member Error : System.Web.Http.Tracing.ITraceWriter * string * Exception * System.Net.Http.HttpRequestMessage * string -&gt; unit" Usage="System.Web.Http.TraceWriterExtensions.Error (traceWriter, message, exception, request, category)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1026:DefaultParametersShouldNotBeUsed", Justification="Default parameters are in order for log messages.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="traceWriter" Type="System.Web.Http.Tracing.ITraceWriter" RefType="this" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="exception" Type="System.Exception" />
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" />
        <Parameter Name="category" Type="System.String">
          <Attributes>
            <Attribute>
              <AttributeName>System.Runtime.CompilerServices.CallerMemberName</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="traceWriter"><span data-ttu-id="29c8b-123">Der <see cref="T:System.Web.Http.Tracing.ITraceWriter" /></span><span class="sxs-lookup"><span data-stu-id="29c8b-123">The <see cref="T:System.Web.Http.Tracing.ITraceWriter" /></span></span></param>
        <param name="message"><span data-ttu-id="29c8b-124">Die zu protokollierende Meldung.</span><span class="sxs-lookup"><span data-stu-id="29c8b-124">The message to log.</span></span></param>
        <param name="exception"><span data-ttu-id="29c8b-125">Die zu protokollierende Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="29c8b-125">The exception to log.</span></span></param>
        <param name="request"><span data-ttu-id="29c8b-126">Anforderung für die Nachrichtenkorrelation verwendet.</span><span class="sxs-lookup"><span data-stu-id="29c8b-126">Request used for message correlation.</span></span> <span data-ttu-id="29c8b-127">Der Standardwert ist null.</span><span class="sxs-lookup"><span data-stu-id="29c8b-127">Defaults to null.</span></span></param>
        <param name="category"><span data-ttu-id="29c8b-128">Die Kategorie für die Ablaufverfolgung.</span><span class="sxs-lookup"><span data-stu-id="29c8b-128">The category for the trace.</span></span> <span data-ttu-id="29c8b-129">Der Standardwert ist die Methode oder Eigenschaft den Namen des Aufrufers.</span><span class="sxs-lookup"><span data-stu-id="29c8b-129">Defaults to the method or property name of the caller.</span></span></param>
        <summary>
            <span data-ttu-id="29c8b-130">Schreibt eine <see cref="T:System.Web.Http.Tracing.TraceRecord" /> am <see cref="F:System.Web.Http.Tracing.TraceLevel.Error" /> mit der angegebenen Meldung und Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="29c8b-130">Writes a <see cref="T:System.Web.Http.Tracing.TraceRecord" /> at <see cref="F:System.Web.Http.Tracing.TraceLevel.Error" /> with the given message and exception.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Info">
      <MemberSignature Language="C#" Value="public static void Info (this System.Web.Http.Tracing.ITraceWriter traceWriter, string message, System.Net.Http.HttpRequestMessage request = null, string category = &quot;&quot;);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Info(class System.Web.Http.Tracing.ITraceWriter traceWriter, string message, class System.Net.Http.HttpRequestMessage request, string category) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Web.Http.TraceWriterExtensions.Info(System.Web.Http.Tracing.ITraceWriter,System.String,System.Net.Http.HttpRequestMessage,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Info (traceWriter As ITraceWriter, message As String, Optional request As HttpRequestMessage = null, Optional category As String = &quot;&quot;)" />
      <MemberSignature Language="F#" Value="static member Info : System.Web.Http.Tracing.ITraceWriter * string * System.Net.Http.HttpRequestMessage * string -&gt; unit" Usage="System.Web.Http.TraceWriterExtensions.Info (traceWriter, message, request, category)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1026:DefaultParametersShouldNotBeUsed", Justification="Default parameters are in order for log messages.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="traceWriter" Type="System.Web.Http.Tracing.ITraceWriter" RefType="this" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" />
        <Parameter Name="category" Type="System.String">
          <Attributes>
            <Attribute>
              <AttributeName>System.Runtime.CompilerServices.CallerMemberName</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="traceWriter"><span data-ttu-id="29c8b-131">Der <see cref="T:System.Web.Http.Tracing.ITraceWriter" /></span><span class="sxs-lookup"><span data-stu-id="29c8b-131">The <see cref="T:System.Web.Http.Tracing.ITraceWriter" /></span></span></param>
        <param name="message"><span data-ttu-id="29c8b-132">Die zu protokollierende Meldung.</span><span class="sxs-lookup"><span data-stu-id="29c8b-132">The message to log.</span></span></param>
        <param name="request"><span data-ttu-id="29c8b-133">Anforderung für die Nachrichtenkorrelation verwendet.</span><span class="sxs-lookup"><span data-stu-id="29c8b-133">Request used for message correlation.</span></span> <span data-ttu-id="29c8b-134">Der Standardwert ist null.</span><span class="sxs-lookup"><span data-stu-id="29c8b-134">Defaults to null.</span></span></param>
        <param name="category"><span data-ttu-id="29c8b-135">Die Kategorie für die Ablaufverfolgung.</span><span class="sxs-lookup"><span data-stu-id="29c8b-135">The category for the trace.</span></span> <span data-ttu-id="29c8b-136">Der Standardwert ist die Methode oder Eigenschaft den Namen des Aufrufers.</span><span class="sxs-lookup"><span data-stu-id="29c8b-136">Defaults to the method or property name of the caller.</span></span></param>
        <summary>
            <span data-ttu-id="29c8b-137">Schreibt eine <see cref="T:System.Web.Http.Tracing.TraceRecord" /> am <see cref="F:System.Web.Http.Tracing.TraceLevel.Info" /> mit der angegebenen Meldung.</span><span class="sxs-lookup"><span data-stu-id="29c8b-137">Writes a <see cref="T:System.Web.Http.Tracing.TraceRecord" /> at <see cref="F:System.Web.Http.Tracing.TraceLevel.Info" /> with the given message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Trace">
      <MemberSignature Language="C#" Value="public static void Trace (this System.Web.Http.Tracing.ITraceWriter traceWriter, System.Web.Http.Tracing.TraceLevel level, string message, Exception exception, System.Net.Http.HttpRequestMessage request = null, string category = &quot;&quot;);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Trace(class System.Web.Http.Tracing.ITraceWriter traceWriter, valuetype System.Web.Http.Tracing.TraceLevel level, string message, class System.Exception exception, class System.Net.Http.HttpRequestMessage request, string category) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Web.Http.TraceWriterExtensions.Trace(System.Web.Http.Tracing.ITraceWriter,System.Web.Http.Tracing.TraceLevel,System.String,System.Exception,System.Net.Http.HttpRequestMessage,System.String)" />
      <MemberSignature Language="F#" Value="static member Trace : System.Web.Http.Tracing.ITraceWriter * System.Web.Http.Tracing.TraceLevel * string * Exception * System.Net.Http.HttpRequestMessage * string -&gt; unit" Usage="System.Web.Http.TraceWriterExtensions.Trace (traceWriter, level, message, exception, request, category)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="traceWriter" Type="System.Web.Http.Tracing.ITraceWriter" RefType="this" />
        <Parameter Name="level" Type="System.Web.Http.Tracing.TraceLevel" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="exception" Type="System.Exception" />
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" />
        <Parameter Name="category" Type="System.String">
          <Attributes>
            <Attribute>
              <AttributeName>System.Runtime.CompilerServices.CallerMemberName</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="traceWriter"><span data-ttu-id="29c8b-138">Der <see cref="T:System.Web.Http.Tracing.ITraceWriter" /></span><span class="sxs-lookup"><span data-stu-id="29c8b-138">The <see cref="T:System.Web.Http.Tracing.ITraceWriter" /></span></span></param>
        <param name="level"><span data-ttu-id="29c8b-139">Die <see cref="T:System.Web.Http.Tracing.TraceLevel" /> für die Ablaufverfolgung.</span><span class="sxs-lookup"><span data-stu-id="29c8b-139">The <see cref="T:System.Web.Http.Tracing.TraceLevel" /> for the trace.</span></span></param>
        <param name="message"><span data-ttu-id="29c8b-140">Die Meldung, die Protokolldateien (oder Null).</span><span class="sxs-lookup"><span data-stu-id="29c8b-140">The message to log (or null).</span></span></param>
        <param name="exception"><span data-ttu-id="29c8b-141">Die Ausnahme, die Protokolldateien (oder Null).</span><span class="sxs-lookup"><span data-stu-id="29c8b-141">The exception to log (or null).</span></span></param>
        <param name="request"><span data-ttu-id="29c8b-142">Anforderung für die Nachrichtenkorrelation verwendet.</span><span class="sxs-lookup"><span data-stu-id="29c8b-142">Request used for message correlation.</span></span> <span data-ttu-id="29c8b-143">Der Standardwert ist null.</span><span class="sxs-lookup"><span data-stu-id="29c8b-143">Defaults to null.</span></span></param>
        <param name="category"><span data-ttu-id="29c8b-144">Die Kategorie für die Ablaufverfolgung.</span><span class="sxs-lookup"><span data-stu-id="29c8b-144">The category for the trace.</span></span> <span data-ttu-id="29c8b-145">Der Standardwert ist die Methode oder Eigenschaft den Namen des Aufrufers.</span><span class="sxs-lookup"><span data-stu-id="29c8b-145">Defaults to the method or property name of the caller.</span></span></param>
        <summary>
            <span data-ttu-id="29c8b-146">Schreibt einen einzelnen <see cref="T:System.Web.Http.Tracing.TraceRecord" /> auf den angegebenen <see cref="T:System.Web.Http.Tracing.ITraceWriter" /> der ablaufverfolgungswriter für aktiviert ist die angegebene <paramref name="category" /> und <paramref name="level" />.</span><span class="sxs-lookup"><span data-stu-id="29c8b-146">Writes a single <see cref="T:System.Web.Http.Tracing.TraceRecord" /> to the given <see cref="T:System.Web.Http.Tracing.ITraceWriter" /> if the trace writer is enabled for the given <paramref name="category" /> and <paramref name="level" />.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Warn">
      <MemberSignature Language="C#" Value="public static void Warn (this System.Web.Http.Tracing.ITraceWriter traceWriter, string message, System.Net.Http.HttpRequestMessage request = null, string category = &quot;&quot;);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Warn(class System.Web.Http.Tracing.ITraceWriter traceWriter, string message, class System.Net.Http.HttpRequestMessage request, string category) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Web.Http.TraceWriterExtensions.Warn(System.Web.Http.Tracing.ITraceWriter,System.String,System.Net.Http.HttpRequestMessage,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Warn (traceWriter As ITraceWriter, message As String, Optional request As HttpRequestMessage = null, Optional category As String = &quot;&quot;)" />
      <MemberSignature Language="F#" Value="static member Warn : System.Web.Http.Tracing.ITraceWriter * string * System.Net.Http.HttpRequestMessage * string -&gt; unit" Usage="System.Web.Http.TraceWriterExtensions.Warn (traceWriter, message, request, category)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1026:DefaultParametersShouldNotBeUsed", Justification="Default parameters are in order for log messages.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="traceWriter" Type="System.Web.Http.Tracing.ITraceWriter" RefType="this" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" />
        <Parameter Name="category" Type="System.String">
          <Attributes>
            <Attribute>
              <AttributeName>System.Runtime.CompilerServices.CallerMemberName</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="traceWriter"><span data-ttu-id="29c8b-147">Der <see cref="T:System.Web.Http.Tracing.ITraceWriter" /></span><span class="sxs-lookup"><span data-stu-id="29c8b-147">The <see cref="T:System.Web.Http.Tracing.ITraceWriter" /></span></span></param>
        <param name="message"><span data-ttu-id="29c8b-148">Die zu protokollierende Meldung.</span><span class="sxs-lookup"><span data-stu-id="29c8b-148">The message to log.</span></span></param>
        <param name="request"><span data-ttu-id="29c8b-149">Anforderung für die Nachrichtenkorrelation verwendet.</span><span class="sxs-lookup"><span data-stu-id="29c8b-149">Request used for message correlation.</span></span> <span data-ttu-id="29c8b-150">Der Standardwert ist null.</span><span class="sxs-lookup"><span data-stu-id="29c8b-150">Defaults to null.</span></span></param>
        <param name="category"><span data-ttu-id="29c8b-151">Die Kategorie für die Ablaufverfolgung.</span><span class="sxs-lookup"><span data-stu-id="29c8b-151">The category for the trace.</span></span> <span data-ttu-id="29c8b-152">Der Standardwert ist die Methode oder Eigenschaft den Namen des Aufrufers.</span><span class="sxs-lookup"><span data-stu-id="29c8b-152">Defaults to the method or property name of the caller.</span></span></param>
        <summary>
            <span data-ttu-id="29c8b-153">Schreibt eine <see cref="T:System.Web.Http.Tracing.TraceRecord" /> am <see cref="F:System.Web.Http.Tracing.TraceLevel.Warn" /> mit der angegebenen Meldung.</span><span class="sxs-lookup"><span data-stu-id="29c8b-153">Writes a <see cref="T:System.Web.Http.Tracing.TraceRecord" /> at <see cref="F:System.Web.Http.Tracing.TraceLevel.Warn" /> with the given message.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>