<Type Name="SharedAccessFileHeaders" FullName="Microsoft.WindowsAzure.Storage.File.SharedAccessFileHeaders">
  <TypeSignature Language="C#" Value="public sealed class SharedAccessFileHeaders" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit SharedAccessFileHeaders extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFileHeaders" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class SharedAccessFileHeaders" />
  <TypeSignature Language="F#" Value="type SharedAccessFileHeaders = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="1e814-101">Stellt die optionalen Header, die mit Dateien, die über SAS zugegriffen zurückgegeben werden können.</span><span class="sxs-lookup"><span data-stu-id="1e814-101">Represents the optional headers that can be returned with files accessed using SAS.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessFileHeaders ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.SharedAccessFileHeaders.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="1e814-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFileHeaders" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="1e814-102">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFileHeaders" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SharedAccessFileHeaders (Microsoft.WindowsAzure.Storage.File.SharedAccessFileHeaders sharedAccessFileHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.File.SharedAccessFileHeaders sharedAccessFileHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.SharedAccessFileHeaders.#ctor(Microsoft.WindowsAzure.Storage.File.SharedAccessFileHeaders)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.File.SharedAccessFileHeaders : Microsoft.WindowsAzure.Storage.File.SharedAccessFileHeaders -&gt; Microsoft.WindowsAzure.Storage.File.SharedAccessFileHeaders" Usage="new Microsoft.WindowsAzure.Storage.File.SharedAccessFileHeaders sharedAccessFileHeaders" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="sharedAccessFileHeaders" Type="Microsoft.WindowsAzure.Storage.File.SharedAccessFileHeaders" />
      </Parameters>
      <Docs>
        <param name="sharedAccessFileHeaders"><span data-ttu-id="1e814-103">Der Satz von <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFileHeaders" /> klonen.</span><span class="sxs-lookup"><span data-stu-id="1e814-103">The set of <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFileHeaders" /> to clone.</span></span></param>
        <summary>
            <span data-ttu-id="1e814-104">Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFileHeaders" /> -Klasse auf Grundlage einer vorhandenen Instanz.</span><span class="sxs-lookup"><span data-stu-id="1e814-104">Initializes a new instance of the <see cref="T:Microsoft.WindowsAzure.Storage.File.SharedAccessFileHeaders" /> class based on an existing instance.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CacheControl">
      <MemberSignature Language="C#" Value="public string CacheControl { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CacheControl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.SharedAccessFileHeaders.CacheControl" />
      <MemberSignature Language="VB.NET" Value="Public Property CacheControl As String" />
      <MemberSignature Language="F#" Value="member this.CacheControl : string with get, set" Usage="Microsoft.WindowsAzure.Storage.File.SharedAccessFileHeaders.CacheControl" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e814-105">Ruft ab oder legt die Cache-Control-Header, die mit der Datei zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="1e814-105">Gets or sets the cache-control header returned with the file.</span></span>
            </summary>
        <value><span data-ttu-id="1e814-106">Eine Zeichenfolge, die den Cache-Control-Wert enthält.</span><span class="sxs-lookup"><span data-stu-id="1e814-106">A string containing the cache-control value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentDisposition">
      <MemberSignature Language="C#" Value="public string ContentDisposition { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentDisposition" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.SharedAccessFileHeaders.ContentDisposition" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentDisposition As String" />
      <MemberSignature Language="F#" Value="member this.ContentDisposition : string with get, set" Usage="Microsoft.WindowsAzure.Storage.File.SharedAccessFileHeaders.ContentDisposition" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e814-107">Ruft ab oder legt den Content-Disposition-Header mit der Datei zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="1e814-107">Gets or sets the content-disposition header returned with the file.</span></span>
            </summary>
        <value><span data-ttu-id="1e814-108">Eine Zeichenfolge mit der Content-Disposition-Wert.</span><span class="sxs-lookup"><span data-stu-id="1e814-108">A string containing the content-disposition value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentEncoding">
      <MemberSignature Language="C#" Value="public string ContentEncoding { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentEncoding" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.SharedAccessFileHeaders.ContentEncoding" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentEncoding As String" />
      <MemberSignature Language="F#" Value="member this.ContentEncoding : string with get, set" Usage="Microsoft.WindowsAzure.Storage.File.SharedAccessFileHeaders.ContentEncoding" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e814-109">Ruft ab, oder legt ihn fest Content-encoding-Headers, der mit der Datei zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="1e814-109">Gets or sets the content-encoding header returned with the file.</span></span>
            </summary>
        <value><span data-ttu-id="1e814-110">Eine Zeichenfolge mit der Content-encoding-Wert.</span><span class="sxs-lookup"><span data-stu-id="1e814-110">A string containing the content-encoding value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentLanguage">
      <MemberSignature Language="C#" Value="public string ContentLanguage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentLanguage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.SharedAccessFileHeaders.ContentLanguage" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentLanguage As String" />
      <MemberSignature Language="F#" Value="member this.ContentLanguage : string with get, set" Usage="Microsoft.WindowsAzure.Storage.File.SharedAccessFileHeaders.ContentLanguage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e814-111">Ruft ab oder legt den Content-Language-Headers, der mit der Datei zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="1e814-111">Gets or sets the content-language header returned with the file.</span></span>
            </summary>
        <value><span data-ttu-id="1e814-112">Eine Zeichenfolge mit der Content-Language-Wert.</span><span class="sxs-lookup"><span data-stu-id="1e814-112">A string containing the content-language value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContentType">
      <MemberSignature Language="C#" Value="public string ContentType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ContentType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.SharedAccessFileHeaders.ContentType" />
      <MemberSignature Language="VB.NET" Value="Public Property ContentType As String" />
      <MemberSignature Language="F#" Value="member this.ContentType : string with get, set" Usage="Microsoft.WindowsAzure.Storage.File.SharedAccessFileHeaders.ContentType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="1e814-113">Ruft ab oder legt den Content-Type-Header, die mit der Datei zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="1e814-113">Gets or sets the content-type header returned with the file.</span></span>
            </summary>
        <value><span data-ttu-id="1e814-114">Eine Zeichenfolge mit der Content-Type-Wert.</span><span class="sxs-lookup"><span data-stu-id="1e814-114">A string containing the content-type value.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>