<Type Name="CreationSource" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.CreationSource">
  <TypeSignature Language="C#" Value="public class CreationSource" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CreationSource extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.CreationSource" />
  <TypeSignature Language="VB.NET" Value="Public Class CreationSource" />
  <TypeSignature Language="F#" Value="type CreationSource = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
             <span data-ttu-id="bb653-101">Die Quelle, aus der verwalteten Datenträger oder einer Momentaufnahme erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="bb653-101">The source from which managed disk or snapshot is created.</span></span>
             </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CreationSource (Microsoft.Azure.Management.Compute.Fluent.Models.CreationData creationData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Management.Compute.Fluent.Models.CreationData creationData) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.CreationSource.#ctor(Microsoft.Azure.Management.Compute.Fluent.Models.CreationData)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.CreationSource : Microsoft.Azure.Management.Compute.Fluent.Models.CreationData -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.CreationSource" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.CreationSource creationData" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="creationData" Type="Microsoft.Azure.Management.Compute.Fluent.Models.CreationData" />
      </Parameters>
      <Docs>
        <param name="creationData"><span data-ttu-id="bb653-102">Das Erstellungsdatum des verwalteten Datenträger oder einer Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="bb653-102">The creation data of managed disk or snapshot.</span></span></param>
        <summary>
             <span data-ttu-id="bb653-103">DiskSource wird erstellt.</span><span class="sxs-lookup"><span data-stu-id="bb653-103">Creates DiskSource.</span></span>
             </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceDataDiskImageLun">
      <MemberSignature Language="C#" Value="public int SourceDataDiskImageLun ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance int32 SourceDataDiskImageLun() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.CreationSource.SourceDataDiskImageLun" />
      <MemberSignature Language="VB.NET" Value="Public Function SourceDataDiskImageLun () As Integer" />
      <MemberSignature Language="F#" Value="member this.SourceDataDiskImageLun : unit -&gt; int" Usage="creationSource.SourceDataDiskImageLun " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>
             <span data-ttu-id="bb653-104">Die Lun-Wert des Datenträgerimages Daten bei der dieses Datenträgers oder einer Momentaufnahme eines Daten-Datenträger-Image,-1 andernfalls Erstellung von.</span><span class="sxs-lookup"><span data-stu-id="bb653-104">The lun value of the data disk image if this disk or snapshot is created from a data disk image, -1 otherwise.</span></span>
             </return>
      </Docs>
    </Member>
    <Member MemberName="SourceId">
      <MemberSignature Language="C#" Value="public string SourceId ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string SourceId() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.CreationSource.SourceId" />
      <MemberSignature Language="VB.NET" Value="Public Function SourceId () As String" />
      <MemberSignature Language="F#" Value="member this.SourceId : unit -&gt; string" Usage="creationSource.SourceId " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="bb653-105">Die ID der Quelle.</span><span class="sxs-lookup"><span data-stu-id="bb653-105">Id of the source.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Type">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.CreationSourceType Type { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CreationSourceType Type" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.CreationSource.Type" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Type As CreationSourceType" />
      <MemberSignature Language="F#" Value="member this.Type : Microsoft.Azure.Management.Compute.Fluent.Models.CreationSourceType" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.CreationSource.Type" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.CreationSourceType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="bb653-106">Der Typ der Quelle aus der Festplatte oder einer Momentaufnahme erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="bb653-106">Type of the source from which disk or snapshot is created.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>