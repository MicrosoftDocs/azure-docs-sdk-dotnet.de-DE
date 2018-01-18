<Type Name="Endpoints" FullName="Microsoft.Azure.Management.Storage.Models.Endpoints">
  <TypeSignature Language="C#" Value="public class Endpoints" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Endpoints extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Storage.Models.Endpoints" />
  <TypeSignature Language="VB.NET" Value="Public Class Endpoints" />
  <TypeSignature Language="F#" Value="type Endpoints = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
    <AssemblyVersion>7.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="83f67-101">Die URIs, die für den Abruf von einer öffentlichen BLOB-, Warteschlangen- oder Tabellenobjekts verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="83f67-101">The URIs that are used to perform a retrieval of a public blob, queue, or table object.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Endpoints ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.Endpoints.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="83f67-102">Initialisiert eine neue Instanz der Klasse Endpunkte an.</span><span class="sxs-lookup"><span data-stu-id="83f67-102">Initializes a new instance of the Endpoints class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Endpoints (string blob = null, string queue = null, string table = null, string file = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string blob, string queue, string table, string file) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Storage.Models.Endpoints.#ctor(System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional blob As String = null, Optional queue As String = null, Optional table As String = null, Optional file As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Storage.Models.Endpoints : string * string * string * string -&gt; Microsoft.Azure.Management.Storage.Models.Endpoints" Usage="new Microsoft.Azure.Management.Storage.Models.Endpoints (blob, queue, table, file)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="blob" Type="System.String" />
        <Parameter Name="queue" Type="System.String" />
        <Parameter Name="table" Type="System.String" />
        <Parameter Name="file" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="blob"><span data-ttu-id="83f67-103">Ruft den blobendpunkt ab.</span><span class="sxs-lookup"><span data-stu-id="83f67-103">Gets the blob endpoint.</span></span></param>
        <param name="queue"><span data-ttu-id="83f67-104">Ruft den Warteschlangendienst-Endpunkt ab.</span><span class="sxs-lookup"><span data-stu-id="83f67-104">Gets the queue endpoint.</span></span></param>
        <param name="table"><span data-ttu-id="83f67-105">Ruft den tabellenspeicherdienst-Endpunkt ab.</span><span class="sxs-lookup"><span data-stu-id="83f67-105">Gets the table endpoint.</span></span></param>
        <param name="file"><span data-ttu-id="83f67-106">Ruft die Dateidienst-Endpunkt ab.</span><span class="sxs-lookup"><span data-stu-id="83f67-106">Gets the file endpoint.</span></span></param>
        <summary>
            <span data-ttu-id="83f67-107">Initialisiert eine neue Instanz der Klasse Endpunkte an.</span><span class="sxs-lookup"><span data-stu-id="83f67-107">Initializes a new instance of the Endpoints class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Blob">
      <MemberSignature Language="C#" Value="public string Blob { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Blob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Endpoints.Blob" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Blob As String" />
      <MemberSignature Language="F#" Value="member this.Blob : string" Usage="Microsoft.Azure.Management.Storage.Models.Endpoints.Blob" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="blob")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83f67-108">Ruft den blobendpunkt ab.</span><span class="sxs-lookup"><span data-stu-id="83f67-108">Gets the blob endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="File">
      <MemberSignature Language="C#" Value="public string File { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string File" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Endpoints.File" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property File As String" />
      <MemberSignature Language="F#" Value="member this.File : string" Usage="Microsoft.Azure.Management.Storage.Models.Endpoints.File" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="file")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83f67-109">Ruft die Dateidienst-Endpunkt ab.</span><span class="sxs-lookup"><span data-stu-id="83f67-109">Gets the file endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Queue">
      <MemberSignature Language="C#" Value="public string Queue { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Queue" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Endpoints.Queue" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Queue As String" />
      <MemberSignature Language="F#" Value="member this.Queue : string" Usage="Microsoft.Azure.Management.Storage.Models.Endpoints.Queue" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="queue")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83f67-110">Ruft den Warteschlangendienst-Endpunkt ab.</span><span class="sxs-lookup"><span data-stu-id="83f67-110">Gets the queue endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Table">
      <MemberSignature Language="C#" Value="public string Table { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Table" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Storage.Models.Endpoints.Table" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Table As String" />
      <MemberSignature Language="F#" Value="member this.Table : string" Usage="Microsoft.Azure.Management.Storage.Models.Endpoints.Table" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Storage</AssemblyName>
        <AssemblyVersion>7.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="table")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="83f67-111">Ruft den tabellenspeicherdienst-Endpunkt ab.</span><span class="sxs-lookup"><span data-stu-id="83f67-111">Gets the table endpoint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>