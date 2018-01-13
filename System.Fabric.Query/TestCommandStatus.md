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
            Diese Klasse stellt den Status eines Test-Befehls dar.  Aufrufen von <see cref="M:System.Fabric.FabricClient.TestManagementClient.GetTestCommandStatusListAsync(System.Fabric.Query.TestCommandStateFilter,System.Fabric.Query.TestCommandTypeFilter,System.TimeSpan,System.Threading.CancellationToken)" /> IList dieser Art von Objekt zurückgibt.
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
            Der OperationId des testbefehls.  Diese Guid wurde vom Benutzer bereitgestellte, beim Starten der Testvorgang.
            </summary>
        <value>Eine Guid, die die OperationId darstellt.</value>
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
            Der aktuelle Zustand des testbefehls.
            </summary>
        <value>Eine TestCommandProgressState mit dem aktuellen Status.</value>
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
            Der Typ des testbefehls.
            </summary>
        <value>Ein TestCommandType-Objekt.</value>
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
            Formate OperationId, Status und den Aktionstyp in eine Zeichenfolge.
            </summary>
        <returns>Die formatierte Zeichenfolge.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>