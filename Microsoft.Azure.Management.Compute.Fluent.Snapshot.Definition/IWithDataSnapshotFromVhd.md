<Type Name="IWithDataSnapshotFromVhd" FullName="Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithDataSnapshotFromVhd">
  <TypeSignature Language="C#" Value="public interface IWithDataSnapshotFromVhd" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDataSnapshotFromVhd" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithDataSnapshotFromVhd" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDataSnapshotFromVhd" />
  <TypeSignature Language="F#" Value="type IWithDataSnapshotFromVhd = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e8c00-101">Die Phase der Definition des verwalteten Datenträger, sodass Quelldaten auswählen auf den Datenträger VHD.</span><span class="sxs-lookup"><span data-stu-id="e8c00-101">The stage of the managed disk definition allowing to choose source data disk VHD.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDataFromVhd">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate WithDataFromVhd (string vhdUrl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate WithDataFromVhd(string vhdUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithDataSnapshotFromVhd.WithDataFromVhd(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDataFromVhd (vhdUrl As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithDataFromVhd : string -&gt; Microsoft.Azure.Management.Compute.Fluent.Snapshot.Definition.IWithCreate" Usage="iWithDataSnapshotFromVhd.WithDataFromVhd vhdUrl" />
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
        <param name="vhdUrl"><span data-ttu-id="e8c00-102">Die Quelle des VHD-URL.</span><span class="sxs-lookup"><span data-stu-id="e8c00-102">A source VHD URL.</span></span></param>
        <summary>
            <span data-ttu-id="e8c00-103">Gibt die Daten der virtuellen Festplatte an.</span><span class="sxs-lookup"><span data-stu-id="e8c00-103">Specifies the source data VHD.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="e8c00-104">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="e8c00-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>