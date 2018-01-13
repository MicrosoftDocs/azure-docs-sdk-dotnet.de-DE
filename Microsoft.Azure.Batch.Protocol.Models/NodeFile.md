<Type Name="NodeFile" FullName="Microsoft.Azure.Batch.Protocol.Models.NodeFile">
  <TypeSignature Language="C#" Value="public class NodeFile" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NodeFile extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.NodeFile" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeFile" />
  <TypeSignature Language="F#" Value="type NodeFile = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5ec5b-101">Informationen zu einer Datei oder eines Verzeichnisses auf einem Serverknoten.</span><span class="sxs-lookup"><span data-stu-id="5ec5b-101">Information about a file or directory on a compute node.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeFile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NodeFile.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5ec5b-102">Initialisiert eine neue Instanz der NodeFile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5ec5b-102">Initializes a new instance of the NodeFile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeFile (string name = null, string url = null, Nullable&lt;bool&gt; isDirectory = null, Microsoft.Azure.Batch.Protocol.Models.FileProperties properties = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string name, string url, valuetype System.Nullable`1&lt;bool&gt; isDirectory, class Microsoft.Azure.Batch.Protocol.Models.FileProperties properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NodeFile.#ctor(System.String,System.String,System.Nullable{System.Boolean},Microsoft.Azure.Batch.Protocol.Models.FileProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional name As String = null, Optional url As String = null, Optional isDirectory As Nullable(Of Boolean) = null, Optional properties As FileProperties = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.NodeFile : string * string * Nullable&lt;bool&gt; * Microsoft.Azure.Batch.Protocol.Models.FileProperties -&gt; Microsoft.Azure.Batch.Protocol.Models.NodeFile" Usage="new Microsoft.Azure.Batch.Protocol.Models.NodeFile (name, url, isDirectory, properties)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="url" Type="System.String" />
        <Parameter Name="isDirectory" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="properties" Type="Microsoft.Azure.Batch.Protocol.Models.FileProperties" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="5ec5b-103">Der Dateipfad.</span><span class="sxs-lookup"><span data-stu-id="5ec5b-103">The file path.</span></span></param>
        <param name="url"><span data-ttu-id="5ec5b-104">Die URL der Datei.</span><span class="sxs-lookup"><span data-stu-id="5ec5b-104">The URL of the file.</span></span></param>
        <param name="isDirectory"><span data-ttu-id="5ec5b-105">Gibt an, ob das Objekt ein Verzeichnis darstellt.</span><span class="sxs-lookup"><span data-stu-id="5ec5b-105">Whether the object represents a directory.</span></span></param>
        <param name="properties"><span data-ttu-id="5ec5b-106">Die Dateieigenschaften.</span><span class="sxs-lookup"><span data-stu-id="5ec5b-106">The file properties.</span></span></param>
        <summary>
            <span data-ttu-id="5ec5b-107">Initialisiert eine neue Instanz der NodeFile-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5ec5b-107">Initializes a new instance of the NodeFile class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDirectory">
      <MemberSignature Language="C#" Value="public Nullable&lt;bool&gt; IsDirectory { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;bool&gt; IsDirectory" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NodeFile.IsDirectory" />
      <MemberSignature Language="VB.NET" Value="Public Property IsDirectory As Nullable(Of Boolean)" />
      <MemberSignature Language="F#" Value="member this.IsDirectory : Nullable&lt;bool&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NodeFile.IsDirectory" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="isDirectory")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5ec5b-108">Ruft ab oder legt fest, ob das Objekt ein Verzeichnis darstellt.</span><span class="sxs-lookup"><span data-stu-id="5ec5b-108">Gets or sets whether the object represents a directory.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NodeFile.Name" />
      <MemberSignature Language="VB.NET" Value="Public Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NodeFile.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="name")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5ec5b-109">Ruft ab oder legt den Dateipfad fest.</span><span class="sxs-lookup"><span data-stu-id="5ec5b-109">Gets or sets the file path.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Properties">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.FileProperties Properties { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.FileProperties Properties" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NodeFile.Properties" />
      <MemberSignature Language="VB.NET" Value="Public Property Properties As FileProperties" />
      <MemberSignature Language="F#" Value="member this.Properties : Microsoft.Azure.Batch.Protocol.Models.FileProperties with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NodeFile.Properties" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="properties")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.FileProperties</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5ec5b-110">Ruft ab oder legt die Dateieigenschaften fest.</span><span class="sxs-lookup"><span data-stu-id="5ec5b-110">Gets or sets the file properties.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Url">
      <MemberSignature Language="C#" Value="public string Url { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Url" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NodeFile.Url" />
      <MemberSignature Language="VB.NET" Value="Public Property Url As String" />
      <MemberSignature Language="F#" Value="member this.Url : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NodeFile.Url" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="url")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5ec5b-111">Ruft ab oder legt die URL der Datei fest.</span><span class="sxs-lookup"><span data-stu-id="5ec5b-111">Gets or sets the URL of the file.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NodeFile.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="nodeFile.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="5ec5b-112">Überprüfen Sie das Objekt.</span><span class="sxs-lookup"><span data-stu-id="5ec5b-112">Validate the object.</span></span>
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="5ec5b-113">Wird ausgelöst, wenn die Validierung fehlschlägt</span><span class="sxs-lookup"><span data-stu-id="5ec5b-113">Thrown if validation fails</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>