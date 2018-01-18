<Type Name="TestCommandStatus" FullName="System.Fabric.Query.TestCommandStatus">
  <TypeSignature Language="C#" Value="public sealed class TestCommandStatus" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit TestCommandStatus extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.Query.TestCommandStatus" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class TestCommandStatus" />
  <TypeSignature Language="F#" Value="type TestCommandStatus = class" />
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
            <span data-ttu-id="0d86d-101">Diese Klasse stellt den Status eines Test-Befehls dar.</span><span class="sxs-lookup"><span data-stu-id="0d86d-101">This class represents the status of a test command.</span></span>  <span data-ttu-id="0d86d-102">Aufrufen von <see cref="M:System.Fabric.FabricClient.TestManagementClient.GetTestCommandStatusListAsync(System.Fabric.Query.TestCommandStateFilter,System.Fabric.Query.TestCommandTypeFilter,System.TimeSpan,System.Threading.CancellationToken)" /> IList dieser Art von Objekt zurückgibt.</span><span class="sxs-lookup"><span data-stu-id="0d86d-102">Calling <see cref="M:System.Fabric.FabricClient.TestManagementClient.GetTestCommandStatusListAsync(System.Fabric.Query.TestCommandStateFilter,System.Fabric.Query.TestCommandTypeFilter,System.TimeSpan,System.Threading.CancellationToken)" /> returns an IList of this type of object.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="OperationId">
      <MemberSignature Language="C#" Value="public Guid OperationId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Guid OperationId" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.TestCommandStatus.OperationId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationId As Guid" />
      <MemberSignature Language="F#" Value="member this.OperationId : Guid" Usage="System.Fabric.Query.TestCommandStatus.OperationId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Guid</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0d86d-103">Der OperationId des testbefehls.</span><span class="sxs-lookup"><span data-stu-id="0d86d-103">The OperationId of the test command.</span></span>  <span data-ttu-id="0d86d-104">Diese Guid wurde vom Benutzer bereitgestellte, beim Starten der Testvorgang.</span><span class="sxs-lookup"><span data-stu-id="0d86d-104">This Guid was provided by the user when starting the test operation.</span></span>
            </summary>
        <value><span data-ttu-id="0d86d-105">Eine Guid, die die OperationId darstellt.</span><span class="sxs-lookup"><span data-stu-id="0d86d-105">A Guid representing the OperationId.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public System.Fabric.TestCommandProgressState State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.TestCommandProgressState State" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.TestCommandStatus.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As TestCommandProgressState" />
      <MemberSignature Language="F#" Value="member this.State : System.Fabric.TestCommandProgressState" Usage="System.Fabric.Query.TestCommandStatus.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TestCommandProgressState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0d86d-106">Der aktuelle Zustand des testbefehls.</span><span class="sxs-lookup"><span data-stu-id="0d86d-106">The current state of the test command.</span></span>
            </summary>
        <value><span data-ttu-id="0d86d-107">Eine TestCommandProgressState mit dem aktuellen Status.</span><span class="sxs-lookup"><span data-stu-id="0d86d-107">A TestCommandProgressState with the current state.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TestCommandType">
      <MemberSignature Language="C#" Value="public System.Fabric.TestCommandType TestCommandType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Fabric.TestCommandType TestCommandType" />
      <MemberSignature Language="DocId" Value="P:System.Fabric.Query.TestCommandStatus.TestCommandType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TestCommandType As TestCommandType" />
      <MemberSignature Language="F#" Value="member this.TestCommandType : System.Fabric.TestCommandType" Usage="System.Fabric.Query.TestCommandStatus.TestCommandType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Fabric.TestCommandType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="0d86d-108">Der Typ des testbefehls.</span><span class="sxs-lookup"><span data-stu-id="0d86d-108">The type of the test command.</span></span>
            </summary>
        <value><span data-ttu-id="0d86d-109">Ein TestCommandType-Objekt.</span><span class="sxs-lookup"><span data-stu-id="0d86d-109">A TestCommandType object.</span></span></value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.Query.TestCommandStatus.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="testCommandStatus.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="0d86d-110">Formate OperationId, Status und den Aktionstyp in eine Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="0d86d-110">Formats OperationId, State, and ActionType into a string.</span></span>
            </summary>
        <returns><span data-ttu-id="0d86d-111">Die formatierte Zeichenfolge.</span><span class="sxs-lookup"><span data-stu-id="0d86d-111">The formatted string.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>