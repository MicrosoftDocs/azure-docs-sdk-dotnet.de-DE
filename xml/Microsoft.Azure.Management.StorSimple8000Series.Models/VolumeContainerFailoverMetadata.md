<Type Name="VolumeContainerFailoverMetadata" FullName="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainerFailoverMetadata">
  <TypeSignature Language="C#" Value="public class VolumeContainerFailoverMetadata" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit VolumeContainerFailoverMetadata extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainerFailoverMetadata" />
  <TypeSignature Language="VB.NET" Value="Public Class VolumeContainerFailoverMetadata" />
  <TypeSignature Language="F#" Value="type VolumeContainerFailoverMetadata = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d1ee0-101">Die Metadaten der volumecontainer, der als Teil einer Reihe Failover angesehen wird.</span><span class="sxs-lookup"><span data-stu-id="d1ee0-101">The metadata of the volume container, that is being considered as part of a failover set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VolumeContainerFailoverMetadata ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainerFailoverMetadata.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d1ee0-102">Initialisiert eine neue Instanz der VolumeContainerFailoverMetadata-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d1ee0-102">Initializes a new instance of the VolumeContainerFailoverMetadata class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public VolumeContainerFailoverMetadata (string volumeContainerId = null, System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeFailoverMetadata&gt; volumes = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string volumeContainerId, class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeFailoverMetadata&gt; volumes) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainerFailoverMetadata.#ctor(System.String,System.Collections.Generic.IList{Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeFailoverMetadata})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional volumeContainerId As String = null, Optional volumes As IList(Of VolumeFailoverMetadata) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainerFailoverMetadata : string * System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeFailoverMetadata&gt; -&gt; Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainerFailoverMetadata" Usage="new Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainerFailoverMetadata (volumeContainerId, volumes)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="volumeContainerId" Type="System.String" />
        <Parameter Name="volumes" Type="System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeFailoverMetadata&gt;" />
      </Parameters>
      <Docs>
        <param name="volumeContainerId"><span data-ttu-id="d1ee0-103">Die Pfad-ID des volumecontainers.</span><span class="sxs-lookup"><span data-stu-id="d1ee0-103">The path ID of the volume container.</span></span></param>
        <param name="volumes"><span data-ttu-id="d1ee0-104">Die Liste der Metadaten der Volumes im Volume-Container, die gültige Cloud-Momentaufnahmen enthält.</span><span class="sxs-lookup"><span data-stu-id="d1ee0-104">The list of metadata of volumes inside the volume container, which contains valid cloud snapshots.</span></span></param>
        <summary>
            <span data-ttu-id="d1ee0-105">Initialisiert eine neue Instanz der VolumeContainerFailoverMetadata-Klasse.</span><span class="sxs-lookup"><span data-stu-id="d1ee0-105">Initializes a new instance of the VolumeContainerFailoverMetadata class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VolumeContainerId">
      <MemberSignature Language="C#" Value="public string VolumeContainerId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string VolumeContainerId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainerFailoverMetadata.VolumeContainerId" />
      <MemberSignature Language="VB.NET" Value="Public Property VolumeContainerId As String" />
      <MemberSignature Language="F#" Value="member this.VolumeContainerId : string with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainerFailoverMetadata.VolumeContainerId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="volumeContainerId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d1ee0-106">Ruft ab oder legt die Pfad-ID des Volume-Container.</span><span class="sxs-lookup"><span data-stu-id="d1ee0-106">Gets or sets the path ID of the volume container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Volumes">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeFailoverMetadata&gt; Volumes { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeFailoverMetadata&gt; Volumes" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainerFailoverMetadata.Volumes" />
      <MemberSignature Language="VB.NET" Value="Public Property Volumes As IList(Of VolumeFailoverMetadata)" />
      <MemberSignature Language="F#" Value="member this.Volumes : System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeFailoverMetadata&gt; with get, set" Usage="Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeContainerFailoverMetadata.Volumes" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.StorSimple8000Series</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="volumes")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Management.StorSimple8000Series.Models.VolumeFailoverMetadata&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d1ee0-107">Ruft ab oder legt die Liste der Metadaten der Volumes im Volume-Container, die gültige Cloud-Momentaufnahmen enthält.</span><span class="sxs-lookup"><span data-stu-id="d1ee0-107">Gets or sets the list of metadata of volumes inside the volume container, which contains valid cloud snapshots.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>