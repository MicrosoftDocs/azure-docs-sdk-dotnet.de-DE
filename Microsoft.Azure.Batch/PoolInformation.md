<Type Name="PoolInformation" FullName="Microsoft.Azure.Batch.PoolInformation">
  <TypeSignature Language="C#" Value="public class PoolInformation" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit PoolInformation extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.PoolInformation" />
  <TypeSignature Language="VB.NET" Value="Public Class PoolInformation" />
  <TypeSignature Language="F#" Value="type PoolInformation = class&#xA;    interface ITransportObjectProvider&lt;PoolInformation&gt;&#xA;    interface IPropertyMetadata&#xA;    interface IModifiable&#xA;    interface IReadOnly" />
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
            <span data-ttu-id="5ead4-101">Gibt an, wie ein Auftrag zu einem Pool zugewiesen werden soll.</span><span class="sxs-lookup"><span data-stu-id="5ead4-101">Specifies how a job should be assigned to a pool.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public PoolInformation ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PoolInformation.#ctor" />
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
            <span data-ttu-id="5ead4-102">Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.PoolInformation" />-Klasse.</span><span class="sxs-lookup"><span data-stu-id="5ead4-102">Initializes a new instance of the <see cref="T:Microsoft.Azure.Batch.PoolInformation" /> class.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoPoolSpecification">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.AutoPoolSpecification AutoPoolSpecification { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.AutoPoolSpecification AutoPoolSpecification" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolInformation.AutoPoolSpecification" />
      <MemberSignature Language="VB.NET" Value="Public Property AutoPoolSpecification As AutoPoolSpecification" />
      <MemberSignature Language="F#" Value="member this.AutoPoolSpecification : Microsoft.Azure.Batch.AutoPoolSpecification with get, set" Usage="Microsoft.Azure.Batch.PoolInformation.AutoPoolSpecification" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.AutoPoolSpecification</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="5ead4-103">Ruft ab oder legt die Eigenschaften für den automatischen Pool, der erstellt wird.</span><span class="sxs-lookup"><span data-stu-id="5ead4-103">Gets or sets the properties for the auto pool that will be created.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="5ead4-104">Wenn diese Eigenschaft, klicken Sie dann festgelegt ist <see cref="P:Microsoft.Azure.Batch.PoolInformation.PoolId" /> unset belassen werden müssen.</span><span class="sxs-lookup"><span data-stu-id="5ead4-104">If this property is set, then <see cref="P:Microsoft.Azure.Batch.PoolInformation.PoolId" /> must be left unset.</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolId">
      <MemberSignature Language="C#" Value="public string PoolId { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PoolId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.PoolInformation.PoolId" />
      <MemberSignature Language="VB.NET" Value="Public Property PoolId As String" />
      <MemberSignature Language="F#" Value="member this.PoolId : string with get, set" Usage="Microsoft.Azure.Batch.PoolInformation.PoolId" />
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
            <span data-ttu-id="5ead4-105">Ruft ab oder legt den Namen eines vorhandenen Pools, die zum Ausführen von Aufgaben verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="5ead4-105">Gets or sets the name of an existing pool that can be used for running tasks.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
            <span data-ttu-id="5ead4-106">Wenn diese Eigenschaft, klicken Sie dann festgelegt ist <see cref="P:Microsoft.Azure.Batch.PoolInformation.AutoPoolSpecification" /> unset belassen werden müssen.</span><span class="sxs-lookup"><span data-stu-id="5ead4-106">If this property is set, then <see cref="P:Microsoft.Azure.Batch.PoolInformation.AutoPoolSpecification" /> must be left unset.</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>