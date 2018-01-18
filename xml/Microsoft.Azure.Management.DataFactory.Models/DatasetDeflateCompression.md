<Type Name="DatasetDeflateCompression" FullName="Microsoft.Azure.Management.DataFactory.Models.DatasetDeflateCompression">
  <TypeSignature Language="C#" Value="public class DatasetDeflateCompression : Microsoft.Azure.Management.DataFactory.Models.DatasetCompression" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit DatasetDeflateCompression extends Microsoft.Azure.Management.DataFactory.Models.DatasetCompression" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactory.Models.DatasetDeflateCompression" />
  <TypeSignature Language="VB.NET" Value="Public Class DatasetDeflateCompression&#xA;Inherits DatasetCompression" />
  <TypeSignature Language="F#" Value="type DatasetDeflateCompression = class&#xA;    inherit DatasetCompression" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
    <AssemblyVersion>0.2.0.0</AssemblyVersion>
    <AssemblyVersion>0.3.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactory.Models.DatasetCompression</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Newtonsoft.Json.JsonObject("Deflate")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="c55c5-101">Die Deflate-Komprimierung-Methode für ein Dataset verwendet.</span><span class="sxs-lookup"><span data-stu-id="c55c5-101">The Deflate compression method used on a dataset.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DatasetDeflateCompression ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.DatasetDeflateCompression.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="c55c5-102">Initialisiert eine neue Instanz der DatasetDeflateCompression-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c55c5-102">Initializes a new instance of the DatasetDeflateCompression class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public DatasetDeflateCompression (System.Collections.Generic.IDictionary&lt;string,object&gt; additionalProperties = null, string level = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Collections.Generic.IDictionary`2&lt;string, object&gt; additionalProperties, string level) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactory.Models.DatasetDeflateCompression.#ctor(System.Collections.Generic.IDictionary{System.String,System.Object},System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional additionalProperties As IDictionary(Of String, Object) = null, Optional level As String = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.DataFactory.Models.DatasetDeflateCompression : System.Collections.Generic.IDictionary&lt;string, obj&gt; * string -&gt; Microsoft.Azure.Management.DataFactory.Models.DatasetDeflateCompression" Usage="new Microsoft.Azure.Management.DataFactory.Models.DatasetDeflateCompression (additionalProperties, level)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="additionalProperties" Type="System.Collections.Generic.IDictionary&lt;System.String,System.Object&gt;" />
        <Parameter Name="level" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="additionalProperties"><span data-ttu-id="c55c5-103">Nicht übereinstimmende Eigenschaften aus der Nachricht deserialisiert werden diese Sammlung</span><span class="sxs-lookup"><span data-stu-id="c55c5-103">Unmatched properties from the message are deserialized this collection</span></span></param>
        <param name="level"><span data-ttu-id="c55c5-104">Die Ebene des Deflate-Komprimierung.</span><span class="sxs-lookup"><span data-stu-id="c55c5-104">The Deflate compression level.</span></span> <span data-ttu-id="c55c5-105">Folgende Werte sind möglich: "Optimal", "Fastest"</span><span class="sxs-lookup"><span data-stu-id="c55c5-105">Possible values include: 'Optimal', 'Fastest'</span></span></param>
        <summary>
            <span data-ttu-id="c55c5-106">Initialisiert eine neue Instanz der DatasetDeflateCompression-Klasse.</span><span class="sxs-lookup"><span data-stu-id="c55c5-106">Initializes a new instance of the DatasetDeflateCompression class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Level">
      <MemberSignature Language="C#" Value="public string Level { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Level" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactory.Models.DatasetDeflateCompression.Level" />
      <MemberSignature Language="VB.NET" Value="Public Property Level As String" />
      <MemberSignature Language="F#" Value="member this.Level : string with get, set" Usage="Microsoft.Azure.Management.DataFactory.Models.DatasetDeflateCompression.Level" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactory</AssemblyName>
        <AssemblyVersion>0.2.0.0</AssemblyVersion>
        <AssemblyVersion>0.3.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="level")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c55c5-107">Ruft ab oder legt die Deflate-Komprimierungsebene.</span><span class="sxs-lookup"><span data-stu-id="c55c5-107">Gets or sets the Deflate compression level.</span></span> <span data-ttu-id="c55c5-108">Folgende Werte sind möglich: "Optimal", "Fastest"</span><span class="sxs-lookup"><span data-stu-id="c55c5-108">Possible values include: 'Optimal', 'Fastest'</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>