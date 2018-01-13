<Type Name="NodeAgentSku" FullName="Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku">
  <TypeSignature Language="C#" Value="public class NodeAgentSku" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NodeAgentSku extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeAgentSku" />
  <TypeSignature Language="F#" Value="type NodeAgentSku = class" />
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
            Eine Knoten-Agent-SKU, die vom Batch-Dienst unterstützt.
            </summary>
    <remarks>
            Der Batch-Knoten-Agent ist ein Programm, das auf jedem Knoten im Pool ausgeführt wird, und stellt eine Schnittstelle Befehl Steuerelement zwischen den Knoten und der Batch-Dienst. Es gibt verschiedene Implementierungen des Knoten-Agents (SKUs) für verschiedene Betriebssysteme.
            </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeAgentSku ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku.#ctor" />
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
            Initialisiert eine neue Instanz der NodeAgentSku-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public NodeAgentSku (string id = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ImageReference&gt; verifiedImageReferences = null, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OSType&gt; osType = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string id, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ImageReference&gt; verifiedImageReferences, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OSType&gt; osType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Batch.Protocol.Models.ImageReference},System.Nullable{Microsoft.Azure.Batch.Protocol.Models.OSType})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional id As String = null, Optional verifiedImageReferences As IList(Of ImageReference) = null, Optional osType As Nullable(Of OSType) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ImageReference&gt; * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OSType&gt; -&gt; Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku" Usage="new Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku (id, verifiedImageReferences, osType)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="id" Type="System.String" />
        <Parameter Name="verifiedImageReferences" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ImageReference&gt;" />
        <Parameter Name="osType" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OSType&gt;" />
      </Parameters>
      <Docs>
        <param name="id">Die ID des Knotens Agents SKU.</param>
        <param name="verifiedImageReferences">Die Liste der Azure Marketplace-Images, die kompatibel mit dieser Knoten-Agent-SKU.</param>
        <param name="osType">Der Typ des Betriebssystems (z. B. Windows oder Linux) mit dem Knoten Agent SKU kompatibel.</param>
        <summary>
            Initialisiert eine neue Instanz der NodeAgentSku-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku.Id" />
      <MemberSignature Language="VB.NET" Value="Public Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="id")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die ID des Knotens Agents SKU fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OsType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OSType&gt; OsType { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.OSType&gt; OsType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku.OsType" />
      <MemberSignature Language="VB.NET" Value="Public Property OsType As Nullable(Of OSType)" />
      <MemberSignature Language="F#" Value="member this.OsType : Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OSType&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku.OsType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="osType")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.OSType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Typ des Betriebssystems (z. B. Windows oder Linux) mit dem Knoten Agent SKU kompatibel.
            </summary>
        <value>To be added.</value>
        <remarks>
            Folgende Werte sind möglich: "Linux", "Windows"
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifiedImageReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ImageReference&gt; VerifiedImageReferences { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ImageReference&gt; VerifiedImageReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku.VerifiedImageReferences" />
      <MemberSignature Language="VB.NET" Value="Public Property VerifiedImageReferences As IList(Of ImageReference)" />
      <MemberSignature Language="F#" Value="member this.VerifiedImageReferences : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ImageReference&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.Models.NodeAgentSku.VerifiedImageReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="verifiedImageReferences")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.Protocol.Models.ImageReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Liste der Azure Marketplace-Images, die kompatibel mit dieser Knoten-Agent-SKU.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Sammlung ist nicht vollständig (der Knoten-Agent kann mit anderen Bildern kompatibel sein).
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>