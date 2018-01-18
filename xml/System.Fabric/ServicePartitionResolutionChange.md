<Type Name="ServicePartitionResolutionChange" FullName="System.Fabric.ServicePartitionResolutionChange">
  <TypeSignature Language="C#" Value="public sealed class ServicePartitionResolutionChange" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit ServicePartitionResolutionChange extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.ServicePartitionResolutionChange" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class ServicePartitionResolutionChange" />
  <TypeSignature Language="F#" Value="type ServicePartitionResolutionChange = class" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="24c5e-101">Dieser Wrapper enthält die aktualisierte <see cref="T:System.Fabric.ResolvedServicePartition" />.</span><span class="sxs-lookup"><span data-stu-id="24c5e-101">This wrapper contains the updated <see cref="T:System.Fabric.ResolvedServicePartition" />.</span></span> </para>
    </summary>
    <remarks>
      <para><span data-ttu-id="24c5e-102">Wenn es eine Ausnahme ausgelöst werden, während die neueren wurde <see cref="T:System.Fabric.ResolvedServicePartition" /> eingerichtet, und klicken Sie dann die <see cref="T:System.Fabric.ServicePartitionResolutionChange" /> enthält auch die Ausnahme.</span><span class="sxs-lookup"><span data-stu-id="24c5e-102">If there was an exception thrown while the newer <see cref="T:System.Fabric.ResolvedServicePartition" /> is acquired, then the <see cref="T:System.Fabric.ServicePartitionResolutionChange" /> also contains the exception.</span></span> <span data-ttu-id="24c5e-103">Beachten Sie, dass bei der <see cref="P:System.Fabric.ServicePartitionResolutionChange.Exception" /> -Eigenschaft nicht null ist, und klicken Sie dann die <see cref="P:System.Fabric.ServicePartitionResolutionChange.Result" /> -Eigenschaft null ist.</span><span class="sxs-lookup"><span data-stu-id="24c5e-103">Note that if the <see cref="P:System.Fabric.ServicePartitionResolutionChange.Exception" /> property is not null, then the <see cref="P:System.Fabric.ServicePartitionResolutionChange.Result" /> property is null.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName="Exception">
      <MemberSignature Language="C#" Value="public Exception Exception { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Exception Exception" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServicePartitionResolutionChange.Exception" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Exception As Exception" />
      <MemberSignature Language="F#" Value="member this.Exception : Exception" Usage="System.Fabric.ServicePartitionResolutionChange.Exception" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Exception</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="24c5e-104">Ruft die Ausnahme, die ausgelöst wurde, während die relevanten <see cref="T:System.Fabric.ResolvedServicePartition" /> , die abgerufen oder aktualisiert wurde.</span><span class="sxs-lookup"><span data-stu-id="24c5e-104">Gets the exception that was thrown while the relevant <see cref="T:System.Fabric.ResolvedServicePartition" /> was being acquired or updated.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="24c5e-105">Gibt <see cref="T:System.Exception" />zurück.</span><span class="sxs-lookup"><span data-stu-id="24c5e-105">Returns <see cref="T:System.Exception" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HasException">
      <MemberSignature Language="C#" Value="public bool HasException { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HasException" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServicePartitionResolutionChange.HasException" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HasException As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasException : bool" Usage="System.Fabric.ServicePartitionResolutionChange.HasException" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="24c5e-106">Gibt an, ob eine Ausnahme aufgetreten.</span><span class="sxs-lookup"><span data-stu-id="24c5e-106">Indicates whether there was an exception.</span></span> </para>
        </summary>
        <value>
          <para><span data-ttu-id="24c5e-107">Gibt <see cref="T:System.Boolean" />zurück.</span><span class="sxs-lookup"><span data-stu-id="24c5e-107">Returns <see cref="T:System.Boolean" />.</span></span></para>
        </value>
        <remarks>
          <para><span data-ttu-id="24c5e-108">Wenn dies der Fall ist, die <see cref="P:System.Fabric.ServicePartitionResolutionChange.Result" /> Parameter null ist und die <see cref="P:System.Fabric.ServicePartitionResolutionChange.Exception" /> Parameter festgelegt ist.</span><span class="sxs-lookup"><span data-stu-id="24c5e-108">If so, the <see cref="P:System.Fabric.ServicePartitionResolutionChange.Result" /> parameter is null and the <see cref="P:System.Fabric.ServicePartitionResolutionChange.Exception" /> parameter is set.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Result">
      <MemberSignature Language="C#" Value="public System.Fabric.ResolvedServicePartition Result { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Fabric.ResolvedServicePartition Result" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.ServicePartitionResolutionChange.Result" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Result As ResolvedServicePartition" />
      <MemberSignature Language="F#" Value="member this.Result : System.Fabric.ResolvedServicePartition" Usage="System.Fabric.ServicePartitionResolutionChange.Result" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.ResolvedServicePartition</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para><span data-ttu-id="24c5e-109">Enthält die neuen <see cref="T:System.Fabric.ResolvedServicePartition" /> , für die registrierten Dienstpartition relevant ist.</span><span class="sxs-lookup"><span data-stu-id="24c5e-109">Contains the new <see cref="T:System.Fabric.ResolvedServicePartition" /> that is relevant for the registered service partition.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="24c5e-110">Gibt <see cref="T:System.Fabric.ResolvedServicePartition" />zurück.</span><span class="sxs-lookup"><span data-stu-id="24c5e-110">Returns <see cref="T:System.Fabric.ResolvedServicePartition" />.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>