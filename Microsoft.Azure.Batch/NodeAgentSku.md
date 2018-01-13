<Type Name="NodeAgentSku" FullName="Microsoft.Azure.Batch.NodeAgentSku">
  <TypeSignature Language="C#" Value="public class NodeAgentSku" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit NodeAgentSku extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.NodeAgentSku" />
  <TypeSignature Language="VB.NET" Value="Public Class NodeAgentSku" />
  <TypeSignature Language="F#" Value="type NodeAgentSku = class&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            Eine Knoten-Agent-SKU, die vom Batch-Dienst unterstützt. Der Batch-Knoten-Agent ist ein Programm, das auf jedem Knoten im Pool ausgeführt wird, und stellt eine Schnittstelle Befehl Steuerelement zwischen den Knoten und der Batch-Dienst. Es gibt verschiedene Implementierungen des Knoten-Agents (SKUs) für verschiedene Betriebssysteme.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Id">
      <MemberSignature Language="C#" Value="public string Id { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Id" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NodeAgentSku.Id" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Id As String" />
      <MemberSignature Language="F#" Value="member this.Id : string" Usage="Microsoft.Azure.Batch.NodeAgentSku.Id" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Id des Knotens Agents SKU.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSType">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Batch.Common.OSType&gt; OSType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Common.OSType&gt; OSType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NodeAgentSku.OSType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSType As Nullable(Of OSType)" />
      <MemberSignature Language="F#" Value="member this.OSType : Nullable&lt;Microsoft.Azure.Batch.Common.OSType&gt;" Usage="Microsoft.Azure.Batch.NodeAgentSku.OSType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Batch.Common.OSType&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Typ des Betriebssystems ab, mit dem Knoten Agent SKU kompatibel.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifiedImageReferences">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.ImageReference&gt; VerifiedImageReferences { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Batch.ImageReference&gt; VerifiedImageReferences" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.NodeAgentSku.VerifiedImageReferences" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VerifiedImageReferences As IReadOnlyList(Of ImageReference)" />
      <MemberSignature Language="F#" Value="member this.VerifiedImageReferences : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.ImageReference&gt;" Usage="Microsoft.Azure.Batch.NodeAgentSku.VerifiedImageReferences" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Batch.ImageReference&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der Azure Marketplace-Images, die kompatibel mit dieser Knoten-Agent-SKU.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Sammlung ist nicht vollständig (der Knoten-Agent kann mit anderen Bildern kompatibel sein).
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>