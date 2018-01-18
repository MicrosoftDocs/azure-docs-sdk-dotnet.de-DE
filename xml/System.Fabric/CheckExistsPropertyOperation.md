<Type Name="CheckExistsPropertyOperation" FullName="System.Fabric.CheckExistsPropertyOperation">
  <TypeSignature Language="C#" Value="public sealed class CheckExistsPropertyOperation : System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit CheckExistsPropertyOperation extends System.Fabric.PropertyBatchOperation" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.CheckExistsPropertyOperation" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class CheckExistsPropertyOperation&#xA;Inherits PropertyBatchOperation" />
  <TypeSignature Language="F#" Value="type CheckExistsPropertyOperation = class&#xA;    inherit PropertyBatchOperation" />
  <AssemblyInfo>
    <AssemblyName>System.Fabric</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Fabric.PropertyBatchOperation</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
      <para><span data-ttu-id="beeaf-101">Stellt eine <see cref="T:System.Fabric.PropertyBatchOperation" /> , vergleicht das boolesche Vorhandensein einer Eigenschaft mit dem <see cref="P:System.Fabric.CheckExistsPropertyOperation.ExistenceCheck" /> Argument.</span><span class="sxs-lookup"><span data-stu-id="beeaf-101">Represents a <see cref="T:System.Fabric.PropertyBatchOperation" /> that compares the Boolean existence of a property with the <see cref="P:System.Fabric.CheckExistsPropertyOperation.ExistenceCheck" /> argument.</span></span> </para>
    </summary>
    <remarks>
      <para><span data-ttu-id="beeaf-102">Die <see cref="T:System.Fabric.PropertyBatchOperation" /> Vorgang fehlschlägt, wenn die Eigenschaft nicht gleich der <see cref="P:System.Fabric.CheckExistsPropertyOperation.ExistenceCheck" /> Argument.</span><span class="sxs-lookup"><span data-stu-id="beeaf-102">The <see cref="T:System.Fabric.PropertyBatchOperation" /> operation fails if the property is not equal to the <see cref="P:System.Fabric.CheckExistsPropertyOperation.ExistenceCheck" /> argument.</span></span>
            <span data-ttu-id="beeaf-103">Die <see cref="T:System.Fabric.CheckExistsPropertyOperation" /> wird im Allgemeinen als Voraussetzung für die Write-Vorgänge im Batch verwendet.</span><span class="sxs-lookup"><span data-stu-id="beeaf-103">The <see cref="T:System.Fabric.CheckExistsPropertyOperation" /> is generally used as a precondition for the write operations in the batch.</span></span> <span data-ttu-id="beeaf-104">Beachten Sie, dass, wenn mindestens eine <see cref="T:System.Fabric.PropertyBatchOperation" /> ein Fehler auftritt, der gesamte Batch schlägt fehl, und kann nicht übertragen werden.</span><span class="sxs-lookup"><span data-stu-id="beeaf-104">Note that if one <see cref="T:System.Fabric.PropertyBatchOperation" /> fails, the entire batch fails and cannot be committed.</span></span></para>
    </remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CheckExistsPropertyOperation (string propertyName, bool existenceCheck);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string propertyName, bool existenceCheck) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.CheckExistsPropertyOperation.#ctor(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (propertyName As String, existenceCheck As Boolean)" />
      <MemberSignature Language="F#" Value="new System.Fabric.CheckExistsPropertyOperation : string * bool -&gt; System.Fabric.CheckExistsPropertyOperation" Usage="new System.Fabric.CheckExistsPropertyOperation (propertyName, existenceCheck)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="propertyName" Type="System.String" />
        <Parameter Name="existenceCheck" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="propertyName">
          <para><span data-ttu-id="beeaf-105">Der Name der Eigenschaft.</span><span class="sxs-lookup"><span data-stu-id="beeaf-105">The name of the property.</span></span></para>
        </param>
        <param name="existenceCheck">
          <para><span data-ttu-id="beeaf-106">Flag, die angibt, ob die Eigenschaft vorhanden, für den Vorgang sein sollte übergeben.</span><span class="sxs-lookup"><span data-stu-id="beeaf-106">Flag that specifies whether the property should exist for the operation to pass.</span></span></para>
        </param>
        <summary>
          <para><span data-ttu-id="beeaf-107">Instanziiert eine <see cref="T:System.Fabric.CheckExistsPropertyOperation" /> Objekt.</span><span class="sxs-lookup"><span data-stu-id="beeaf-107">Instantiates a <see cref="T:System.Fabric.CheckExistsPropertyOperation" /> object.</span></span> </para>
        </summary>
        <remarks>
          <para><span data-ttu-id="beeaf-108">Wenn alle <see cref="T:System.Fabric.PropertyBatchOperation" /> in den Batch ein Fehler auftritt, der gesamten batch ein Fehler auftritt, und kann nicht übertragen werden.</span><span class="sxs-lookup"><span data-stu-id="beeaf-108">If any <see cref="T:System.Fabric.PropertyBatchOperation" /> in the batch fails, the entire batch fails and cannot be committed.</span></span></para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistenceCheck">
      <MemberSignature Language="C#" Value="public bool ExistenceCheck { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ExistenceCheck" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.CheckExistsPropertyOperation.ExistenceCheck" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExistenceCheck As Boolean" />
      <MemberSignature Language="F#" Value="member this.ExistenceCheck : bool" Usage="System.Fabric.CheckExistsPropertyOperation.ExistenceCheck" />
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
          <para><span data-ttu-id="beeaf-109">Ruft das Flag, die angibt, ob die Eigenschaft vorhanden, für den Vorgang sein sollte übergeben.</span><span class="sxs-lookup"><span data-stu-id="beeaf-109">Gets the flag that specifies whether the property should exist for the operation to pass.</span></span></para>
        </summary>
        <value>
          <para><span data-ttu-id="beeaf-110">Flag, die angibt, ob die Eigenschaft vorhanden, für den Vorgang sein sollte übergeben.</span><span class="sxs-lookup"><span data-stu-id="beeaf-110">Flag that specifies whether the property should exist for the operation to pass.</span></span></para>
        </value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>