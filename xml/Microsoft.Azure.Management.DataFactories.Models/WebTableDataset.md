<Type Name="WebTableDataset" FullName="Microsoft.Azure.Management.DataFactories.Models.WebTableDataset">
  <TypeSignature Language="C#" Value="public class WebTableDataset : Microsoft.Azure.Management.DataFactories.Models.DatasetTypeProperties" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit WebTableDataset extends Microsoft.Azure.Management.DataFactories.Models.DatasetTypeProperties" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.Models.WebTableDataset" />
  <TypeSignature Language="VB.NET" Value="Public Class WebTableDataset&#xA;Inherits DatasetTypeProperties" />
  <TypeSignature Language="F#" Value="type WebTableDataset = class&#xA;    inherit DatasetTypeProperties" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>Microsoft.Azure.Management.DataFactories.Models.DatasetTypeProperties</BaseTypeName>
  </Base>
  <Interfaces />
  <Attributes>
    <Attribute>
      <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfTypeName("WebTable")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            <span data-ttu-id="9e162-101">Eine Webtabelle.</span><span class="sxs-lookup"><span data-stu-id="9e162-101">A web table.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public WebTableDataset ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.Models.WebTableDataset.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Index">
      <MemberSignature Language="C#" Value="public uint Index { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int32 Index" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.WebTableDataset.Index" />
      <MemberSignature Language="VB.NET" Value="Public Property Index As UInteger" />
      <MemberSignature Language="F#" Value="member this.Index : uint32 with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.WebTableDataset.Index" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Management.DataFactories.Models.AdfRequired</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.UInt32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9e162-102">Der nullbasierte Index der Tabelle auf der Webseite.</span><span class="sxs-lookup"><span data-stu-id="9e162-102">The zero-based index of the table in the web page.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PartitionedBy">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Models.Partition&gt; PartitionedBy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.DataFactories.Models.Partition&gt; PartitionedBy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.WebTableDataset.PartitionedBy" />
      <MemberSignature Language="VB.NET" Value="Public Property PartitionedBy As IList(Of Partition)" />
      <MemberSignature Language="F#" Value="member this.PartitionedBy : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Models.Partition&gt; with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.WebTableDataset.PartitionedBy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.DataFactories.Models.Partition&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9e162-103">Die Partitionen, die mit dem Pfad verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="9e162-103">The partitions to be used by the path.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.DataFactories.Models.WebTableDataset.Path" />
      <MemberSignature Language="VB.NET" Value="Public Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string with get, set" Usage="Microsoft.Azure.Management.DataFactories.Models.WebTableDataset.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="9e162-104">Die relative URL zur Webseite aus dem verknüpften Dienst-URL.</span><span class="sxs-lookup"><span data-stu-id="9e162-104">The relative URL to the web page from the linked service URL.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>