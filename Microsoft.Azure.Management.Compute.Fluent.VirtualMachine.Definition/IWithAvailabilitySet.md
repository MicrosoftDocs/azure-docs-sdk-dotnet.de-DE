<Type Name="IWithAvailabilitySet" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithAvailabilitySet">
  <TypeSignature Language="C#" Value="public interface IWithAvailabilitySet" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAvailabilitySet" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithAvailabilitySet" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAvailabilitySet" />
  <TypeSignature Language="F#" Value="type IWithAvailabilitySet = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5455d-101">Legen Sie die Phase der Definition des virtuellen Computer, sodass Verfügbarkeit angeben.</span><span class="sxs-lookup"><span data-stu-id="5455d-101">The stage of the virtual machine definition allowing to specify availability set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingAvailabilitySet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithExistingAvailabilitySet (Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySet availabilitySet);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithExistingAvailabilitySet(class Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySet availabilitySet) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithAvailabilitySet.WithExistingAvailabilitySet(Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySet)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingAvailabilitySet (availabilitySet As IAvailabilitySet) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingAvailabilitySet : Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySet -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate" Usage="iWithAvailabilitySet.WithExistingAvailabilitySet availabilitySet" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="availabilitySet" Type="Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySet" />
      </Parameters>
      <Docs>
        <param name="availabilitySet"><span data-ttu-id="5455d-102">Eine vorhandene verfügbarkeitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="5455d-102">An existing availability set.</span></span></param>
        <summary>
            <span data-ttu-id="5455d-103">Gibt einen vorhandenen verfügbarkeitssatz, den virtuellen Computer zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="5455d-103">Specifies an existing availability set to associate with the virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5455d-104">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="5455d-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewAvailabilitySet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithNewAvailabilitySet (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySet&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithNewAvailabilitySet(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySet&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithAvailabilitySet.WithNewAvailabilitySet(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySet})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewAvailabilitySet (creatable As ICreatable(Of IAvailabilitySet)) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewAvailabilitySet : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySet&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate" Usage="iWithAvailabilitySet.WithNewAvailabilitySet creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Compute.Fluent.IAvailabilitySet&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable"><span data-ttu-id="5455d-105">Die Verfügbarkeit eine erstellbare festgelegt Definition.</span><span class="sxs-lookup"><span data-stu-id="5455d-105">A creatable availability set definition.</span></span></param>
        <summary>
            <span data-ttu-id="5455d-106">Gibt die Definition eine Satzdefinition Verfügbarkeit noch nicht erstellt die virtuelle Maschine mit zuordnen.</span><span class="sxs-lookup"><span data-stu-id="5455d-106">Specifies definition of a not-yet-created availability set definition to associate the virtual machine with.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5455d-107">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="5455d-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewAvailabilitySet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithNewAvailabilitySet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithNewAvailabilitySet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithAvailabilitySet.WithNewAvailabilitySet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewAvailabilitySet (name As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewAvailabilitySet : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate" Usage="iWithAvailabilitySet.WithNewAvailabilitySet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="5455d-108">Der Name der verfügbarkeitsgruppe.</span><span class="sxs-lookup"><span data-stu-id="5455d-108">The name of an availability set.</span></span></param>
        <summary>
            <span data-ttu-id="5455d-109">Gibt den Namen einer neuen verfügbarkeitsgruppe der virtuellen Maschine zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="5455d-109">Specifies the name of a new availability set to associate with the virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="5455d-110">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="5455d-110">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>