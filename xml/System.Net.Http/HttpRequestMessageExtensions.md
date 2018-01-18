<Type Name="HttpRequestMessageExtensions" FullName="System.Net.Http.HttpRequestMessageExtensions">
  <TypeSignature Language="C#" Value="public static class HttpRequestMessageExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit HttpRequestMessageExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Net.Http.HttpRequestMessageExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module HttpRequestMessageExtensions" />
  <TypeSignature Language="F#" Value="type HttpRequestMessageExtensions = class" />
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
            <span data-ttu-id="8f93f-101">Erweiterungsmethoden für <see cref="T:System.Net.Http.HttpRequestMessage" /> verschiedene Hilfsprogramme bereitstellen.</span><span class="sxs-lookup"><span data-stu-id="8f93f-101">Extension methods for <see cref="T:System.Net.Http.HttpRequestMessage" /> providing various utilities.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateBadRequestResponse">
      <MemberSignature Language="C#" Value="public static System.Net.Http.HttpResponseMessage CreateBadRequestResponse (this System.Net.Http.HttpRequestMessage request);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.Http.HttpResponseMessage CreateBadRequestResponse(class System.Net.Http.HttpRequestMessage request) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.CreateBadRequestResponse(System.Net.Http.HttpRequestMessage)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateBadRequestResponse (request As HttpRequestMessage) As HttpResponseMessage" />
      <MemberSignature Language="F#" Value="static member CreateBadRequestResponse : System.Net.Http.HttpRequestMessage -&gt; System.Net.Http.HttpResponseMessage" Usage="System.Net.Http.HttpRequestMessageExtensions.CreateBadRequestResponse request" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", Justification="Parameters are validated by Create due to how extension methods are resolved.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Net.Http.HttpResponseMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
      </Parameters>
      <Docs>
        <param name="request"><span data-ttu-id="8f93f-102">Der aktuelle <see cref="T:System.Net.Http.HttpRequestMessage" />.</span><span class="sxs-lookup"><span data-stu-id="8f93f-102">The current <see cref="T:System.Net.Http.HttpRequestMessage" />.</span></span></param>
        <summary>
            <span data-ttu-id="8f93f-103">Erstellt ein <see cref="T:System.Net.Http.HttpResponseMessage" /> mit einem <see cref="F:System.Net.HttpStatusCode.BadRequest" /> Statuscode und den Standardwert <see cref="T:System.Web.Http.HttpError" /> als HTTP-Antworttext.</span><span class="sxs-lookup"><span data-stu-id="8f93f-103">Creates an <see cref="T:System.Net.Http.HttpResponseMessage" /> with an <see cref="F:System.Net.HttpStatusCode.BadRequest" /> status code and a  default <see cref="T:System.Web.Http.HttpError" /> as HTTP response body.</span></span>
            </summary>
        <returns><span data-ttu-id="8f93f-104">Eine initialisierte <see cref="T:System.Net.Http.HttpResponseMessage" />.</span><span class="sxs-lookup"><span data-stu-id="8f93f-104">An initialized <see cref="T:System.Net.Http.HttpResponseMessage" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateBadRequestResponse">
      <MemberSignature Language="C#" Value="public static System.Net.Http.HttpResponseMessage CreateBadRequestResponse (this System.Net.Http.HttpRequestMessage request, string format, params object[] args);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.Http.HttpResponseMessage CreateBadRequestResponse(class System.Net.Http.HttpRequestMessage request, string format, object[] args) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.CreateBadRequestResponse(System.Net.Http.HttpRequestMessage,System.String,System.Object[])" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateBadRequestResponse (request As HttpRequestMessage, format As String, ParamArray args As Object()) As HttpResponseMessage" />
      <MemberSignature Language="F#" Value="static member CreateBadRequestResponse : System.Net.Http.HttpRequestMessage * string * obj[] -&gt; System.Net.Http.HttpResponseMessage" Usage="System.Net.Http.HttpRequestMessageExtensions.CreateBadRequestResponse (request, format, args)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", Justification="Parameters are validated by Create due to how extension methods are resolved.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Net.Http.HttpResponseMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
        <Parameter Name="format" Type="System.String" />
        <Parameter Name="args" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="request"><span data-ttu-id="8f93f-105">Der aktuelle <see cref="T:System.Net.Http.HttpRequestMessage" />.</span><span class="sxs-lookup"><span data-stu-id="8f93f-105">The current <see cref="T:System.Net.Http.HttpRequestMessage" />.</span></span></param>
        <param name="format"><span data-ttu-id="8f93f-106">Eine kombinierte Formatzeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="8f93f-106">A composite format string.</span></span></param>
        <param name="args"><span data-ttu-id="8f93f-107">Ein Objektarray mit 0 (null) oder mehr zu formatierenden Objekten.</span><span class="sxs-lookup"><span data-stu-id="8f93f-107">An object array that contains zero or more objects to format.</span></span></param>
        <summary>
            <span data-ttu-id="8f93f-108">Erstellt ein <see cref="T:System.Net.Http.HttpResponseMessage" /> mit einer <see cref="F:System.Net.HttpStatusCode.BadRequest" /> Statuscode und einen <see cref="T:System.Web.Http.HttpError" /> mit der angegebenen Meldung als HTTP-Antworttext.</span><span class="sxs-lookup"><span data-stu-id="8f93f-108">Creates an <see cref="T:System.Net.Http.HttpResponseMessage" /> with an <see cref="F:System.Net.HttpStatusCode.BadRequest" /> status code and a <see cref="T:System.Web.Http.HttpError" /> containing the provided message as HTTP response body.</span></span>
            </summary>
        <returns><span data-ttu-id="8f93f-109">Eine initialisierte <see cref="T:System.Net.Http.HttpResponseMessage" />.</span><span class="sxs-lookup"><span data-stu-id="8f93f-109">An initialized <see cref="T:System.Net.Http.HttpResponseMessage" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateNotFoundResponse">
      <MemberSignature Language="C#" Value="public static System.Net.Http.HttpResponseMessage CreateNotFoundResponse (this System.Net.Http.HttpRequestMessage request);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.Http.HttpResponseMessage CreateNotFoundResponse(class System.Net.Http.HttpRequestMessage request) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.CreateNotFoundResponse(System.Net.Http.HttpRequestMessage)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateNotFoundResponse (request As HttpRequestMessage) As HttpResponseMessage" />
      <MemberSignature Language="F#" Value="static member CreateNotFoundResponse : System.Net.Http.HttpRequestMessage -&gt; System.Net.Http.HttpResponseMessage" Usage="System.Net.Http.HttpRequestMessageExtensions.CreateNotFoundResponse request" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", Justification="Parameters are validated by Create due to how extension methods are resolved.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Net.Http.HttpResponseMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
      </Parameters>
      <Docs>
        <param name="request"><span data-ttu-id="8f93f-110">Der aktuelle <see cref="T:System.Net.Http.HttpRequestMessage" />.</span><span class="sxs-lookup"><span data-stu-id="8f93f-110">The current <see cref="T:System.Net.Http.HttpRequestMessage" />.</span></span></param>
        <summary>
            <span data-ttu-id="8f93f-111">Erstellt ein <see cref="T:System.Net.Http.HttpResponseMessage" /> mit einem <see cref="F:System.Net.HttpStatusCode.NotFound" /> Statuscode und den Standardwert <see cref="T:System.Web.Http.HttpError" /> als HTTP-Antworttext.</span><span class="sxs-lookup"><span data-stu-id="8f93f-111">Creates an <see cref="T:System.Net.Http.HttpResponseMessage" /> with an <see cref="F:System.Net.HttpStatusCode.NotFound" /> status code and a default <see cref="T:System.Web.Http.HttpError" /> as HTTP response body.</span></span>
            </summary>
        <returns><span data-ttu-id="8f93f-112">Eine initialisierte <see cref="T:System.Net.Http.HttpResponseMessage" />.</span><span class="sxs-lookup"><span data-stu-id="8f93f-112">An initialized <see cref="T:System.Net.Http.HttpResponseMessage" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateNotFoundResponse">
      <MemberSignature Language="C#" Value="public static System.Net.Http.HttpResponseMessage CreateNotFoundResponse (this System.Net.Http.HttpRequestMessage request, string format, params object[] args);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.Http.HttpResponseMessage CreateNotFoundResponse(class System.Net.Http.HttpRequestMessage request, string format, object[] args) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.CreateNotFoundResponse(System.Net.Http.HttpRequestMessage,System.String,System.Object[])" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateNotFoundResponse (request As HttpRequestMessage, format As String, ParamArray args As Object()) As HttpResponseMessage" />
      <MemberSignature Language="F#" Value="static member CreateNotFoundResponse : System.Net.Http.HttpRequestMessage * string * obj[] -&gt; System.Net.Http.HttpResponseMessage" Usage="System.Net.Http.HttpRequestMessageExtensions.CreateNotFoundResponse (request, format, args)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", Justification="Parameters are validated by Create due to how extension methods are resolved.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Net.Http.HttpResponseMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
        <Parameter Name="format" Type="System.String" />
        <Parameter Name="args" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="request"><span data-ttu-id="8f93f-113">Der aktuelle <see cref="T:System.Net.Http.HttpRequestMessage" />.</span><span class="sxs-lookup"><span data-stu-id="8f93f-113">The current <see cref="T:System.Net.Http.HttpRequestMessage" />.</span></span></param>
        <param name="format"><span data-ttu-id="8f93f-114">Eine kombinierte Formatzeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="8f93f-114">A composite format string.</span></span></param>
        <param name="args"><span data-ttu-id="8f93f-115">Ein Objektarray mit 0 (null) oder mehr zu formatierenden Objekten.</span><span class="sxs-lookup"><span data-stu-id="8f93f-115">An object array that contains zero or more objects to format.</span></span></param>
        <summary>
            <span data-ttu-id="8f93f-116">Erstellt ein <see cref="T:System.Net.Http.HttpResponseMessage" /> mit einer <see cref="F:System.Net.HttpStatusCode.NotFound" /> Statuscode und einen <see cref="T:System.Web.Http.HttpError" /> mit der angegebenen Meldung als HTTP-Antworttext.</span><span class="sxs-lookup"><span data-stu-id="8f93f-116">Creates an <see cref="T:System.Net.Http.HttpResponseMessage" /> with an <see cref="F:System.Net.HttpStatusCode.NotFound" /> status code and a <see cref="T:System.Web.Http.HttpError" /> containing the provided message as HTTP response body.</span></span>
            </summary>
        <returns><span data-ttu-id="8f93f-117">Eine initialisierte <see cref="T:System.Net.Http.HttpResponseMessage" />.</span><span class="sxs-lookup"><span data-stu-id="8f93f-117">An initialized <see cref="T:System.Net.Http.HttpResponseMessage" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUnauthorizedResponse">
      <MemberSignature Language="C#" Value="public static System.Net.Http.HttpResponseMessage CreateUnauthorizedResponse (this System.Net.Http.HttpRequestMessage request);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.Http.HttpResponseMessage CreateUnauthorizedResponse(class System.Net.Http.HttpRequestMessage request) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.CreateUnauthorizedResponse(System.Net.Http.HttpRequestMessage)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateUnauthorizedResponse (request As HttpRequestMessage) As HttpResponseMessage" />
      <MemberSignature Language="F#" Value="static member CreateUnauthorizedResponse : System.Net.Http.HttpRequestMessage -&gt; System.Net.Http.HttpResponseMessage" Usage="System.Net.Http.HttpRequestMessageExtensions.CreateUnauthorizedResponse request" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", Justification="Parameters are validated by Create due to how extension methods are resolved.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Net.Http.HttpResponseMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
      </Parameters>
      <Docs>
        <param name="request"><span data-ttu-id="8f93f-118">Der aktuelle <see cref="T:System.Net.Http.HttpRequestMessage" />.</span><span class="sxs-lookup"><span data-stu-id="8f93f-118">The current <see cref="T:System.Net.Http.HttpRequestMessage" />.</span></span></param>
        <summary>
            <span data-ttu-id="8f93f-119">Erstellt ein <see cref="T:System.Net.Http.HttpResponseMessage" /> mit einem <see cref="F:System.Net.HttpStatusCode.Unauthorized" /> Statuscode und den Standardwert <see cref="T:System.Web.Http.HttpError" /> als HTTP-Antworttext.</span><span class="sxs-lookup"><span data-stu-id="8f93f-119">Creates an <see cref="T:System.Net.Http.HttpResponseMessage" /> with an <see cref="F:System.Net.HttpStatusCode.Unauthorized" /> status code and a  default <see cref="T:System.Web.Http.HttpError" /> as HTTP response body.</span></span>
            </summary>
        <returns><span data-ttu-id="8f93f-120">Eine initialisierte <see cref="T:System.Net.Http.HttpResponseMessage" />.</span><span class="sxs-lookup"><span data-stu-id="8f93f-120">An initialized <see cref="T:System.Net.Http.HttpResponseMessage" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateUnauthorizedResponse">
      <MemberSignature Language="C#" Value="public static System.Net.Http.HttpResponseMessage CreateUnauthorizedResponse (this System.Net.Http.HttpRequestMessage request, string format, params object[] args);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Net.Http.HttpResponseMessage CreateUnauthorizedResponse(class System.Net.Http.HttpRequestMessage request, string format, object[] args) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.CreateUnauthorizedResponse(System.Net.Http.HttpRequestMessage,System.String,System.Object[])" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateUnauthorizedResponse (request As HttpRequestMessage, format As String, ParamArray args As Object()) As HttpResponseMessage" />
      <MemberSignature Language="F#" Value="static member CreateUnauthorizedResponse : System.Net.Http.HttpRequestMessage * string * obj[] -&gt; System.Net.Http.HttpResponseMessage" Usage="System.Net.Http.HttpRequestMessageExtensions.CreateUnauthorizedResponse (request, format, args)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Diagnostics.CodeAnalysis.SuppressMessage("Microsoft.Design", "CA1062:Validate arguments of public methods", Justification="Parameters are validated by Create due to how extension methods are resolved.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Net.Http.HttpResponseMessage</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
        <Parameter Name="format" Type="System.String" />
        <Parameter Name="args" Type="System.Object[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="request"><span data-ttu-id="8f93f-121">Der aktuelle <see cref="T:System.Net.Http.HttpRequestMessage" />.</span><span class="sxs-lookup"><span data-stu-id="8f93f-121">The current <see cref="T:System.Net.Http.HttpRequestMessage" />.</span></span></param>
        <param name="format"><span data-ttu-id="8f93f-122">Eine kombinierte Formatzeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="8f93f-122">A composite format string.</span></span></param>
        <param name="args"><span data-ttu-id="8f93f-123">Ein Objektarray mit 0 (null) oder mehr zu formatierenden Objekten.</span><span class="sxs-lookup"><span data-stu-id="8f93f-123">An object array that contains zero or more objects to format.</span></span></param>
        <summary>
            <span data-ttu-id="8f93f-124">Erstellt ein <see cref="T:System.Net.Http.HttpResponseMessage" /> mit einer <see cref="F:System.Net.HttpStatusCode.Unauthorized" /> Statuscode und einen <see cref="T:System.Web.Http.HttpError" /> mit der angegebenen Meldung als HTTP-Antworttext.</span><span class="sxs-lookup"><span data-stu-id="8f93f-124">Creates an <see cref="T:System.Net.Http.HttpResponseMessage" /> with an <see cref="F:System.Net.HttpStatusCode.Unauthorized" /> status code and a <see cref="T:System.Web.Http.HttpError" /> containing the provided message as HTTP response body.</span></span>
            </summary>
        <returns><span data-ttu-id="8f93f-125">Eine initialisierte <see cref="T:System.Net.Http.HttpResponseMessage" />.</span><span class="sxs-lookup"><span data-stu-id="8f93f-125">An initialized <see cref="T:System.Net.Http.HttpResponseMessage" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHeaderOrDefault">
      <MemberSignature Language="C#" Value="public static string GetHeaderOrDefault (this System.Net.Http.HttpRequestMessage request, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig string GetHeaderOrDefault(class System.Net.Http.HttpRequestMessage request, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.GetHeaderOrDefault(System.Net.Http.HttpRequestMessage,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetHeaderOrDefault (request As HttpRequestMessage, name As String) As String" />
      <MemberSignature Language="F#" Value="static member GetHeaderOrDefault : System.Net.Http.HttpRequestMessage * string -&gt; string" Usage="System.Net.Http.HttpRequestMessageExtensions.GetHeaderOrDefault (request, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="request"><span data-ttu-id="8f93f-126">Die Anforderung, wo der Header gesucht.</span><span class="sxs-lookup"><span data-stu-id="8f93f-126">The request for where to look for the header.</span></span></param>
        <param name="name"><span data-ttu-id="8f93f-127">Der Name des Headers.</span><span class="sxs-lookup"><span data-stu-id="8f93f-127">The name of the header.</span></span></param>
        <summary>
            <span data-ttu-id="8f93f-128">Ruft den ersten HTTP-Header-Wert als einen einzelnen Wert oder <c>null</c> Falls nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="8f93f-128">Gets the first HTTP header value as a single value or <c>null</c> if not present.</span></span>
            </summary>
        <returns><span data-ttu-id="8f93f-129">Der erste Wert des HTTP-Header oder <c>null</c> Falls nicht vorhanden.</span><span class="sxs-lookup"><span data-stu-id="8f93f-129">The first HTTP header value or <c>null</c> if not present.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsIfNoneMatch">
      <MemberSignature Language="C#" Value="public static bool IsIfNoneMatch (this System.Net.Http.HttpRequestMessage request, System.Net.Http.Headers.EntityTagHeaderValue current);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool IsIfNoneMatch(class System.Net.Http.HttpRequestMessage request, class System.Net.Http.Headers.EntityTagHeaderValue current) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Net.Http.HttpRequestMessageExtensions.IsIfNoneMatch(System.Net.Http.HttpRequestMessage,System.Net.Http.Headers.EntityTagHeaderValue)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function IsIfNoneMatch (request As HttpRequestMessage, current As EntityTagHeaderValue) As Boolean" />
      <MemberSignature Language="F#" Value="static member IsIfNoneMatch : System.Net.Http.HttpRequestMessage * System.Net.Http.Headers.EntityTagHeaderValue -&gt; bool" Usage="System.Net.Http.HttpRequestMessageExtensions.IsIfNoneMatch (request, current)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Mobile.Server</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="request" Type="System.Net.Http.HttpRequestMessage" RefType="this" />
        <Parameter Name="current" Type="System.Net.Http.Headers.EntityTagHeaderValue" />
      </Parameters>
      <Docs>
        <param name="request"><span data-ttu-id="8f93f-130">Die Anforderung zu entsprechen.</span><span class="sxs-lookup"><span data-stu-id="8f93f-130">The request to match.</span></span></param>
        <param name="current"><span data-ttu-id="8f93f-131">Das aktuelle Etag der Ressource.</span><span class="sxs-lookup"><span data-stu-id="8f93f-131">The current etag for the resource.</span></span> <span data-ttu-id="8f93f-132">Wenn es keine aktuelle Etag ist (d. h. die Ressource ist noch nicht vorhanden) verwenden Sie <c>null</c>.</span><span class="sxs-lookup"><span data-stu-id="8f93f-132">If there is no current etag (i.e. the resource does not yet exist) then use <c>null</c>.</span></span></param>
        <summary>
            <span data-ttu-id="8f93f-133">Überprüft, ob die Anforderung bedingte ist ein <c>If-None-Match</c> -HTTP-Headerfeld mit einem Wert, entspricht die <paramref name="current" /> Wert.</span><span class="sxs-lookup"><span data-stu-id="8f93f-133">Checks if the request is conditional having a <c>If-None-Match</c> HTTP header field with a value that matches the <paramref name="current" /> value.</span></span> <span data-ttu-id="8f93f-134">Im Fall von <c>"true"</c> Dies kann verwendet werden, um anzugeben, dass eine 304 (nicht geändert) oder einen 412 (Precondition Failed) Statuscode verwendet werden soll.</span><span class="sxs-lookup"><span data-stu-id="8f93f-134">In the case of <c>true</c> this can be used to indicate that a 304 (Not Modified) or a 412 (Precondition Failed) status code should be used.</span></span>
            </summary>
        <returns><span data-ttu-id="8f93f-135">Gibt <c>"true"</c> sofern von der <c>If-None-Match</c> Werten übereinstimmen, die das aktuelle Etag; oder die <c>If-None-Match</c> Wert ist "\*" und <paramref name="current" /> nicht null ist; andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="8f93f-135">Returns <c>true</c> if one of the <c>If-None-Match</c> values match the current etag; or the <c>If-None-Match</c> value is "\*" and <paramref name="current" /> is not null; otherwise false.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>