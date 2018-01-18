<Type Name="IWithWindowsSnapshotSource" FullName="Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithWindowsSnapshotSource">
  <TypeSignature Language="C#" Value="public interface IWithWindowsSnapshotSource" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithWindowsSnapshotSource" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithWindowsSnapshotSource" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithWindowsSnapshotSource" />
  <TypeSignature Language="F#" Value="type IWithWindowsSnapshotSource = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="79dc8-101">Die Phase der verwalteten Momentaufnahmendefinition ermöglicht Windows-Betriebssystem-Quelle auswählen.</span><span class="sxs-lookup"><span data-stu-id="79dc8-101">The stage of the managed snapshot definition allowing to choose Windows OS source.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithWindowsFromDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate WithWindowsFromDisk (Microsoft.Azure.Management.Compute.Fluent.IDisk sourceDisk);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate WithWindowsFromDisk(class Microsoft.Azure.Management.Compute.Fluent.IDisk sourceDisk) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithWindowsSnapshotSource.WithWindowsFromDisk(Microsoft.Azure.Management.Compute.Fluent.IDisk)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWindowsFromDisk (sourceDisk As IDisk) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithWindowsFromDisk : Microsoft.Azure.Management.Compute.Fluent.IDisk -&gt; Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate" Usage="iWithWindowsSnapshotSource.WithWindowsFromDisk sourceDisk" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceDisk" Type="Microsoft.Azure.Management.Compute.Fluent.IDisk" />
      </Parameters>
      <Docs>
        <param name="sourceDisk"><span data-ttu-id="79dc8-102">Eine verwaltete Quelldatenträger.</span><span class="sxs-lookup"><span data-stu-id="79dc8-102">A source managed disk.</span></span></param>
        <summary>
            <span data-ttu-id="79dc8-103">Gibt den verwalteten Windows-Betriebssystems Quelldatenträger an.</span><span class="sxs-lookup"><span data-stu-id="79dc8-103">Specifies the source Windows OS managed disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="79dc8-104">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="79dc8-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithWindowsFromDisk">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate WithWindowsFromDisk (string sourceDiskId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate WithWindowsFromDisk(string sourceDiskId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithWindowsSnapshotSource.WithWindowsFromDisk(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWindowsFromDisk (sourceDiskId As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithWindowsFromDisk : string -&gt; Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate" Usage="iWithWindowsSnapshotSource.WithWindowsFromDisk sourceDiskId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceDiskId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sourceDiskId"><span data-ttu-id="79dc8-105">Eine Quelle verwaltet, Datenträger-Ressourcen-ID.</span><span class="sxs-lookup"><span data-stu-id="79dc8-105">A source managed disk resource ID.</span></span></param>
        <summary>
            <span data-ttu-id="79dc8-106">Gibt den verwalteten Windows-Betriebssystems Quelldatenträger an.</span><span class="sxs-lookup"><span data-stu-id="79dc8-106">Specifies the source Windows OS managed disk.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="79dc8-107">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="79dc8-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithWindowsFromSnapshot">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate WithWindowsFromSnapshot (Microsoft.Azure.Management.Compute.Fluent.ISnapshot sourceSnapshot);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate WithWindowsFromSnapshot(class Microsoft.Azure.Management.Compute.Fluent.ISnapshot sourceSnapshot) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithWindowsSnapshotSource.WithWindowsFromSnapshot(Microsoft.Azure.Management.Compute.Fluent.ISnapshot)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWindowsFromSnapshot (sourceSnapshot As ISnapshot) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithWindowsFromSnapshot : Microsoft.Azure.Management.Compute.Fluent.ISnapshot -&gt; Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate" Usage="iWithWindowsSnapshotSource.WithWindowsFromSnapshot sourceSnapshot" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceSnapshot" Type="Microsoft.Azure.Management.Compute.Fluent.ISnapshot" />
      </Parameters>
      <Docs>
        <param name="sourceSnapshot"><span data-ttu-id="79dc8-108">Eine Quellmomentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="79dc8-108">A source snapshot.</span></span></param>
        <summary>
            <span data-ttu-id="79dc8-109">Gibt die Quelle verwaltete Windows-Betriebssystem-Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="79dc8-109">Specifies the source Windows OS managed snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="79dc8-110">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="79dc8-110">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithWindowsFromSnapshot">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate WithWindowsFromSnapshot (string sourceSnapshotId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate WithWindowsFromSnapshot(string sourceSnapshotId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithWindowsSnapshotSource.WithWindowsFromSnapshot(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWindowsFromSnapshot (sourceSnapshotId As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithWindowsFromSnapshot : string -&gt; Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate" Usage="iWithWindowsSnapshotSource.WithWindowsFromSnapshot sourceSnapshotId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sourceSnapshotId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sourceSnapshotId"><span data-ttu-id="79dc8-111">Eine Snapshot-Ressourcen-ID.</span><span class="sxs-lookup"><span data-stu-id="79dc8-111">A snapshot resource ID.</span></span></param>
        <summary>
            <span data-ttu-id="79dc8-112">Gibt die Quelle verwaltete Windows-Betriebssystem-Momentaufnahme.</span><span class="sxs-lookup"><span data-stu-id="79dc8-112">Specifies the source Windows OS managed snapshot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="79dc8-113">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="79dc8-113">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithWindowsFromVhd">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate WithWindowsFromVhd (string vhdUrl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate WithWindowsFromVhd(string vhdUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithWindowsSnapshotSource.WithWindowsFromVhd(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithWindowsFromVhd (vhdUrl As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithWindowsFromVhd : string -&gt; Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate" Usage="iWithWindowsSnapshotSource.WithWindowsFromVhd vhdUrl" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="vhdUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="vhdUrl"><span data-ttu-id="79dc8-114">Die Quelle VHD-URL.</span><span class="sxs-lookup"><span data-stu-id="79dc8-114">The source VHD URL.</span></span></param>
        <summary>
            <span data-ttu-id="79dc8-115">Gibt die Quelle spezialisiert oder Windows-Betriebssystem-VHD generalisiert.</span><span class="sxs-lookup"><span data-stu-id="79dc8-115">Specifies the source specialized or generalized Windows OS VHD.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="79dc8-116">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="79dc8-116">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>