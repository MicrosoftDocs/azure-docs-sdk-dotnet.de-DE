<Type Name="CorsRule" FullName="Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsRule">
  <TypeSignature Language="C#" Value="public sealed class CorsRule" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CorsRule extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsRule" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CorsRule" />
  <TypeSignature Language="F#" Value="type CorsRule = class" />
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
            <span data-ttu-id="3efa6-101">Klasse, die die Diensteigenschaften für CORS darstellt.</span><span class="sxs-lookup"><span data-stu-id="3efa6-101">Class representing the service properties pertaining to CORS.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CorsRule ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsRule.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowedHeaders">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AllowedHeaders { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AllowedHeaders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsRule.AllowedHeaders" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowedHeaders As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AllowedHeaders : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsRule.AllowedHeaders" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3efa6-102">Abrufen oder Festlegen von Headern, die als Teil der CORS-Anforderung zulässig.</span><span class="sxs-lookup"><span data-stu-id="3efa6-102">Gets or sets headers allowed to be part of the CORS request.</span></span>
            </summary>
        <value><span data-ttu-id="3efa6-103">Eine Auflistung von Zeichenfolgen, zulässige Header enthalten; auf 64 definierte Header und zwei Header mit Präfix begrenzt.</span><span class="sxs-lookup"><span data-stu-id="3efa6-103">A collection of strings containing allowed headers, limited to 64 defined headers and two prefixed headers.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowedMethods">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsHttpMethods AllowedMethods { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsHttpMethods AllowedMethods" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsRule.AllowedMethods" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowedMethods As CorsHttpMethods" />
      <MemberSignature Language="F#" Value="member this.AllowedMethods : Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsHttpMethods with get, set" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsRule.AllowedMethods" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsHttpMethods</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3efa6-104">Ruft ab oder legt die HTTP-Methoden, die für diesen Ursprung ausgeführt werden darf.</span><span class="sxs-lookup"><span data-stu-id="3efa6-104">Gets or sets the HTTP methods permitted to execute for this origin.</span></span>
            </summary>
        <value><span data-ttu-id="3efa6-105">Die zulässigen HTTP-Methoden.</span><span class="sxs-lookup"><span data-stu-id="3efa6-105">The allowed HTTP methods.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AllowedOrigins">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; AllowedOrigins { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; AllowedOrigins" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsRule.AllowedOrigins" />
      <MemberSignature Language="VB.NET" Value="Public Property AllowedOrigins As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.AllowedOrigins : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsRule.AllowedOrigins" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3efa6-106">Ruft ab oder legt die über CORS zulässige Domänennamen fest.</span><span class="sxs-lookup"><span data-stu-id="3efa6-106">Gets or sets domain names allowed via CORS.</span></span>
            </summary>
        <value><span data-ttu-id="3efa6-107">Eine Auflistung von Zeichenfolgen, enthält die zulässigen Domänennamen auf 64 begrenzt.</span><span class="sxs-lookup"><span data-stu-id="3efa6-107">A collection of strings containing the allowed domain names, limited to 64.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExposedHeaders">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; ExposedHeaders { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; ExposedHeaders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsRule.ExposedHeaders" />
      <MemberSignature Language="VB.NET" Value="Public Property ExposedHeaders As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.ExposedHeaders : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsRule.ExposedHeaders" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3efa6-108">Ermittelt oder definiert Antwortheader, die verfügbar gemacht werden sollen, über CORS für den Client.</span><span class="sxs-lookup"><span data-stu-id="3efa6-108">Gets or sets response headers that should be exposed to client via CORS.</span></span>
            </summary>
        <value><span data-ttu-id="3efa6-109">Eine Auflistung von Zeichenfolgen, die verfügbar gemachte Header, auf 64 definierte Header und zwei Header mit Präfix begrenzt.</span><span class="sxs-lookup"><span data-stu-id="3efa6-109">A collection of strings containing exposed headers, limited to 64 defined headers and two prefixed headers.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxAgeInSeconds">
      <MemberSignature Language="C#" Value="public int MaxAgeInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxAgeInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsRule.MaxAgeInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property MaxAgeInSeconds As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxAgeInSeconds : int with get, set" Usage="Microsoft.WindowsAzure.Storage.Shared.Protocol.CorsRule.MaxAgeInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3efa6-110">Ruft ab oder legt die Zeitspanne in Sekunden an, denen eine preflight-Antwort vom Browser zwischengespeichert werden soll.</span><span class="sxs-lookup"><span data-stu-id="3efa6-110">Gets or sets the length of time in seconds that a preflight response should be cached by browser.</span></span>
            </summary>
        <value><span data-ttu-id="3efa6-111">Die maximale Anzahl von Sekunden die Antwort zwischengespeichert werden soll.</span><span class="sxs-lookup"><span data-stu-id="3efa6-111">The maximum number of seconds to cache the response.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>