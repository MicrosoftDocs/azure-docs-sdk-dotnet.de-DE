<Type Name="ComputeNodeOperationsExtensions" FullName="Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ComputeNodeOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ComputeNodeOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ComputeNodeOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ComputeNodeOperationsExtensions = class" />
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
            Erweiterungsmethoden für ComputeNodeOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AddUser">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserHeaders AddUser (this Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser user, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserOptions computeNodeAddUserOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserHeaders AddUser(class Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser user, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserOptions computeNodeAddUserOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.AddUser(Microsoft.Azure.Batch.Protocol.IComputeNodeOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserOptions)" />
      <MemberSignature Language="F#" Value="static member AddUser : Microsoft.Azure.Batch.Protocol.IComputeNodeOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserHeaders" Usage="Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.AddUser (operations, poolId, nodeId, user, computeNodeAddUserOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IComputeNodeOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="user" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser" />
        <Parameter Name="computeNodeAddUserOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID des Computers, auf dem Sie ein Benutzerkonto erstellen möchten.
            </param>
        <param name="user">
            Das Benutzerkonto erstellt werden soll.
            </param>
        <param name="computeNodeAddUserOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Fügt ein Benutzerkonto mit dem angegebenen Computeknoten.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Sie können einen Knoten nur, wenn es in den Status im Leerlauf befindlichen oder ausgeführten ist ein Benutzerkonto hinzufügen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="AddUserAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserHeaders&gt; AddUserAsync (this Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser user, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserOptions computeNodeAddUserOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserHeaders&gt; AddUserAsync(class Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser user, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserOptions computeNodeAddUserOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.AddUserAsync(Microsoft.Azure.Batch.Protocol.IComputeNodeOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AddUserAsync : Microsoft.Azure.Batch.Protocol.IComputeNodeOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.AddUserAsync (operations, poolId, nodeId, user, computeNodeAddUserOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions/&lt;AddUserAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IComputeNodeOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="user" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUser" />
        <Parameter Name="computeNodeAddUserOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeAddUserOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID des Computers, auf dem Sie ein Benutzerkonto erstellen möchten.
            </param>
        <param name="user">
            Das Benutzerkonto erstellt werden soll.
            </param>
        <param name="computeNodeAddUserOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Fügt ein Benutzerkonto mit dem angegebenen Computeknoten.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Sie können einen Knoten nur, wenn es in den Status im Leerlauf befindlichen oder ausgeführten ist ein Benutzerkonto hinzufügen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteUser">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserHeaders DeleteUser (this Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, string userName, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserOptions computeNodeDeleteUserOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserHeaders DeleteUser(class Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, string userName, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserOptions computeNodeDeleteUserOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.DeleteUser(Microsoft.Azure.Batch.Protocol.IComputeNodeOperations,System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserOptions)" />
      <MemberSignature Language="F#" Value="static member DeleteUser : Microsoft.Azure.Batch.Protocol.IComputeNodeOperations * string * string * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserHeaders" Usage="Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.DeleteUser (operations, poolId, nodeId, userName, computeNodeDeleteUserOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IComputeNodeOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="computeNodeDeleteUserOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID des Computers, auf dem Sie ein Benutzerkonto löschen möchten.
            </param>
        <param name="userName">
            Der Name des Benutzerkontos zu löschen.
            </param>
        <param name="computeNodeDeleteUserOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Löscht ein Benutzerkonto aus dem angegebenen Computeknoten.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Sie können ein Benutzerkonto auf einen Knoten löschen, nur, wenn sie den Status im Leerlauf befindet oder ausgeführt wird.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteUserAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserHeaders&gt; DeleteUserAsync (this Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, string userName, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserOptions computeNodeDeleteUserOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserHeaders&gt; DeleteUserAsync(class Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, string userName, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserOptions computeNodeDeleteUserOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.DeleteUserAsync(Microsoft.Azure.Batch.Protocol.IComputeNodeOperations,System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteUserAsync : Microsoft.Azure.Batch.Protocol.IComputeNodeOperations * string * string * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.DeleteUserAsync (operations, poolId, nodeId, userName, computeNodeDeleteUserOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions/&lt;DeleteUserAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IComputeNodeOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="computeNodeDeleteUserOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDeleteUserOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID des Computers, auf dem Sie ein Benutzerkonto löschen möchten.
            </param>
        <param name="userName">
            Der Name des Benutzerkontos zu löschen.
            </param>
        <param name="computeNodeDeleteUserOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht ein Benutzerkonto aus dem angegebenen Computeknoten.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Sie können ein Benutzerkonto auf einen Knoten löschen, nur, wenn sie den Status im Leerlauf befindet oder ausgeführt wird.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableScheduling">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingHeaders DisableScheduling (this Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption&gt; nodeDisableSchedulingOption = null, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingOptions computeNodeDisableSchedulingOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingHeaders DisableScheduling(class Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption&gt; nodeDisableSchedulingOption, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingOptions computeNodeDisableSchedulingOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.DisableScheduling(Microsoft.Azure.Batch.Protocol.IComputeNodeOperations,System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption},Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingOptions)" />
      <MemberSignature Language="F#" Value="static member DisableScheduling : Microsoft.Azure.Batch.Protocol.IComputeNodeOperations * string * string * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption&gt; * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingHeaders" Usage="Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.DisableScheduling (operations, poolId, nodeId, nodeDisableSchedulingOption, computeNodeDisableSchedulingOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IComputeNodeOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="nodeDisableSchedulingOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption&gt;" />
        <Parameter Name="computeNodeDisableSchedulingOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID der Compute-Knoten, auf dem Sie die aufgabenplanung deaktivieren möchten.
            </param>
        <param name="nodeDisableSchedulingOption">
            Was möchten Sie mit den derzeit ausgeführten Aufgaben bei der Deaktivierung der aufgabenplanung auf dem Computeknoten. Der Standardwert ist „requeue“. Folgende Werte sind möglich: "wieder in Warteschlange", "Beenden", "TaskCompletion"
            </param>
        <param name="computeNodeDisableSchedulingOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Deaktiviert die aufgabenplanung auf dem angegebenen Computeknoten.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Sie können Aufgabenplanungsdienstes auf einem Knoten nur, wenn aktuelle scheduling Zustand aktiviert ist, deaktivieren.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableSchedulingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingHeaders&gt; DisableSchedulingAsync (this Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption&gt; nodeDisableSchedulingOption = null, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingOptions computeNodeDisableSchedulingOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingHeaders&gt; DisableSchedulingAsync(class Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption&gt; nodeDisableSchedulingOption, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingOptions computeNodeDisableSchedulingOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.DisableSchedulingAsync(Microsoft.Azure.Batch.Protocol.IComputeNodeOperations,System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption},Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DisableSchedulingAsync : Microsoft.Azure.Batch.Protocol.IComputeNodeOperations * string * string * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption&gt; * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.DisableSchedulingAsync (operations, poolId, nodeId, nodeDisableSchedulingOption, computeNodeDisableSchedulingOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions/&lt;DisableSchedulingAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IComputeNodeOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="nodeDisableSchedulingOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.DisableComputeNodeSchedulingOption&gt;" />
        <Parameter Name="computeNodeDisableSchedulingOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeDisableSchedulingOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID der Compute-Knoten, auf dem Sie die aufgabenplanung deaktivieren möchten.
            </param>
        <param name="nodeDisableSchedulingOption">
            Was möchten Sie mit den derzeit ausgeführten Aufgaben bei der Deaktivierung der aufgabenplanung auf dem Computeknoten. Der Standardwert ist „requeue“. Folgende Werte sind möglich: "wieder in Warteschlange", "Beenden", "TaskCompletion"
            </param>
        <param name="computeNodeDisableSchedulingOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Deaktiviert die aufgabenplanung auf dem angegebenen Computeknoten.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Sie können Aufgabenplanungsdienstes auf einem Knoten nur, wenn aktuelle scheduling Zustand aktiviert ist, deaktivieren.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableScheduling">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingHeaders EnableScheduling (this Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingOptions computeNodeEnableSchedulingOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingHeaders EnableScheduling(class Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingOptions computeNodeEnableSchedulingOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.EnableScheduling(Microsoft.Azure.Batch.Protocol.IComputeNodeOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingOptions)" />
      <MemberSignature Language="F#" Value="static member EnableScheduling : Microsoft.Azure.Batch.Protocol.IComputeNodeOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingHeaders" Usage="Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.EnableScheduling (operations, poolId, nodeId, computeNodeEnableSchedulingOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IComputeNodeOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="computeNodeEnableSchedulingOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID der Compute-Knoten, auf dem Sie die aufgabenplanung aktivieren möchten.
            </param>
        <param name="computeNodeEnableSchedulingOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Ermöglicht die aufgabenplanung auf dem angegebenen Computeknoten.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Sie können Aufgabenplanungsdienstes auf einem Knoten nur, wenn aktuelle scheduling Zustand deaktiviert ist
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableSchedulingAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingHeaders&gt; EnableSchedulingAsync (this Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingOptions computeNodeEnableSchedulingOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingHeaders&gt; EnableSchedulingAsync(class Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingOptions computeNodeEnableSchedulingOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.EnableSchedulingAsync(Microsoft.Azure.Batch.Protocol.IComputeNodeOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member EnableSchedulingAsync : Microsoft.Azure.Batch.Protocol.IComputeNodeOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.EnableSchedulingAsync (operations, poolId, nodeId, computeNodeEnableSchedulingOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions/&lt;EnableSchedulingAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IComputeNodeOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="computeNodeEnableSchedulingOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeEnableSchedulingOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID der Compute-Knoten, auf dem Sie die aufgabenplanung aktivieren möchten.
            </param>
        <param name="computeNodeEnableSchedulingOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ermöglicht die aufgabenplanung auf dem angegebenen Computeknoten.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Sie können Aufgabenplanungsdienstes auf einem Knoten nur, wenn aktuelle scheduling Zustand deaktiviert ist
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.ComputeNode Get (this Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetOptions computeNodeGetOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.ComputeNode Get(class Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetOptions computeNodeGetOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.Get(Microsoft.Azure.Batch.Protocol.IComputeNodeOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Batch.Protocol.IComputeNodeOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.ComputeNode" Usage="Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.Get (operations, poolId, nodeId, computeNodeGetOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNode</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IComputeNodeOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="computeNodeGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID des Serverknotens, die zu dem Informationen abgerufen werden sollen.
            </param>
        <param name="computeNodeGetOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Ruft Informationen über den angegebenen Computeknoten ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt; GetAsync (this Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetOptions computeNodeGetOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt; GetAsync(class Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetOptions computeNodeGetOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.GetAsync(Microsoft.Azure.Batch.Protocol.IComputeNodeOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Batch.Protocol.IComputeNodeOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;" Usage="Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.GetAsync (operations, poolId, nodeId, computeNodeGetOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IComputeNodeOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="computeNodeGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID des Serverknotens, die zu dem Informationen abgerufen werden sollen.
            </param>
        <param name="computeNodeGetOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Informationen über den angegebenen Computeknoten ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRemoteDesktop">
      <MemberSignature Language="C#" Value="public static System.IO.Stream GetRemoteDesktop (this Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopOptions computeNodeGetRemoteDesktopOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.IO.Stream GetRemoteDesktop(class Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopOptions computeNodeGetRemoteDesktopOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.GetRemoteDesktop(Microsoft.Azure.Batch.Protocol.IComputeNodeOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopOptions)" />
      <MemberSignature Language="F#" Value="static member GetRemoteDesktop : Microsoft.Azure.Batch.Protocol.IComputeNodeOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopOptions -&gt; System.IO.Stream" Usage="Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.GetRemoteDesktop (operations, poolId, nodeId, computeNodeGetRemoteDesktopOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.IO.Stream</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IComputeNodeOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="computeNodeGetRemoteDesktopOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID der Compute-Knoten, die für den Remotedesktopprotokoll-Datei abgerufen werden soll.
            </param>
        <param name="computeNodeGetRemoteDesktopOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Ruft die Remotedesktopprotokoll-Datei für den angegebenen Computeknoten ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Bevor Sie einen Knoten mithilfe der RDP-Datei zugreifen können, müssen Sie ein Benutzerkonto auf dem Knoten erstellen. Diese API kann nur auf mit einer Cloud-Service-Konfiguration erstellten Ressourcenpools aufgerufen werden. Mit einer VM-Konfiguration erstellten Ressourcenpools finden Sie unter der GetRemoteLoginSettings-API.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRemoteDesktopAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.IO.Stream&gt; GetRemoteDesktopAsync (this Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopOptions computeNodeGetRemoteDesktopOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.IO.Stream&gt; GetRemoteDesktopAsync(class Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopOptions computeNodeGetRemoteDesktopOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.GetRemoteDesktopAsync(Microsoft.Azure.Batch.Protocol.IComputeNodeOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetRemoteDesktopAsync : Microsoft.Azure.Batch.Protocol.IComputeNodeOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.IO.Stream&gt;" Usage="Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.GetRemoteDesktopAsync (operations, poolId, nodeId, computeNodeGetRemoteDesktopOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions/&lt;GetRemoteDesktopAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.IO.Stream&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IComputeNodeOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="computeNodeGetRemoteDesktopOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteDesktopOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID der Compute-Knoten, die für den Remotedesktopprotokoll-Datei abgerufen werden soll.
            </param>
        <param name="computeNodeGetRemoteDesktopOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die Remotedesktopprotokoll-Datei für den angegebenen Computeknoten ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Bevor Sie einen Knoten mithilfe der RDP-Datei zugreifen können, müssen Sie ein Benutzerkonto auf dem Knoten erstellen. Diese API kann nur auf mit einer Cloud-Service-Konfiguration erstellten Ressourcenpools aufgerufen werden. Mit einer VM-Konfiguration erstellten Ressourcenpools finden Sie unter der GetRemoteLoginSettings-API.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRemoteLoginSettings">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult GetRemoteLoginSettings (this Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsOptions computeNodeGetRemoteLoginSettingsOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult GetRemoteLoginSettings(class Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsOptions computeNodeGetRemoteLoginSettingsOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.GetRemoteLoginSettings(Microsoft.Azure.Batch.Protocol.IComputeNodeOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsOptions)" />
      <MemberSignature Language="F#" Value="static member GetRemoteLoginSettings : Microsoft.Azure.Batch.Protocol.IComputeNodeOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult" Usage="Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.GetRemoteLoginSettings (operations, poolId, nodeId, computeNodeGetRemoteLoginSettingsOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IComputeNodeOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="computeNodeGetRemoteLoginSettingsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID des Serverknotens für die remote-Anmelde-Einstellungen abzurufen.
            </param>
        <param name="computeNodeGetRemoteLoginSettingsOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Ruft die erforderlichen Einstellungen für die Remoteanmeldung an einem Serverknoten an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Bevor Sie Remote können anmelden auf einen Knoten mithilfe der remote-Anmelde-Einstellungen müssen Sie ein Benutzerkonto erstellen, auf dem Knoten. Diese API kann nur auf mit der Eigenschaft der virtuellen Maschine Konfiguration erstellten Ressourcenpools aufgerufen werden. Finden Sie mit einer Cloud-Service-Konfiguration erstellten Ressourcenpools in der GetRemoteDesktop-API.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRemoteLoginSettingsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult&gt; GetRemoteLoginSettingsAsync (this Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsOptions computeNodeGetRemoteLoginSettingsOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult&gt; GetRemoteLoginSettingsAsync(class Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsOptions computeNodeGetRemoteLoginSettingsOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.GetRemoteLoginSettingsAsync(Microsoft.Azure.Batch.Protocol.IComputeNodeOperations,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetRemoteLoginSettingsAsync : Microsoft.Azure.Batch.Protocol.IComputeNodeOperations * string * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult&gt;" Usage="Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.GetRemoteLoginSettingsAsync (operations, poolId, nodeId, computeNodeGetRemoteLoginSettingsOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions/&lt;GetRemoteLoginSettingsAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IComputeNodeOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="computeNodeGetRemoteLoginSettingsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeGetRemoteLoginSettingsOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID des Serverknotens für die remote-Anmelde-Einstellungen abzurufen.
            </param>
        <param name="computeNodeGetRemoteLoginSettingsOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die erforderlichen Einstellungen für die Remoteanmeldung an einem Serverknoten an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Bevor Sie Remote können anmelden auf einen Knoten mithilfe der remote-Anmelde-Einstellungen müssen Sie ein Benutzerkonto erstellen, auf dem Knoten. Diese API kann nur auf mit der Eigenschaft der virtuellen Maschine Konfiguration erstellten Ressourcenpools aufgerufen werden. Finden Sie mit einer Cloud-Service-Konfiguration erstellten Ressourcenpools in der GetRemoteDesktop-API.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt; List (this Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListOptions computeNodeListOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt; List(class Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListOptions computeNodeListOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.List(Microsoft.Azure.Batch.Protocol.IComputeNodeOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Batch.Protocol.IComputeNodeOperations * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;" Usage="Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.List (operations, poolId, computeNodeListOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IComputeNodeOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, aus der Listenknoten werden sollen.
            </param>
        <param name="computeNodeListOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Listet die Serverknoten in den angegebenen Pool.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;&gt; ListAsync (this Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListOptions computeNodeListOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;&gt; ListAsync(class Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListOptions computeNodeListOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.ListAsync(Microsoft.Azure.Batch.Protocol.IComputeNodeOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Batch.Protocol.IComputeNodeOperations * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.ListAsync (operations, poolId, computeNodeListOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions/&lt;ListAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IComputeNodeOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="computeNodeListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, aus der Listenknoten werden sollen.
            </param>
        <param name="computeNodeListOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die Serverknoten in den angegebenen Pool.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt; ListNext (this Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListNextOptions computeNodeListNextOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt; ListNext(class Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListNextOptions computeNodeListNextOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.ListNext(Microsoft.Azure.Batch.Protocol.IComputeNodeOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListNextOptions)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Batch.Protocol.IComputeNodeOperations * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListNextOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;" Usage="Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.ListNext (operations, nextPageLink, computeNodeListNextOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IComputeNodeOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="computeNodeListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListNextOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="computeNodeListNextOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Listet die Serverknoten in den angegebenen Pool.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;&gt; ListNextAsync (this Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListNextOptions computeNodeListNextOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;&gt; ListNextAsync(class Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListNextOptions computeNodeListNextOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.ListNextAsync(Microsoft.Azure.Batch.Protocol.IComputeNodeOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListNextOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Batch.Protocol.IComputeNodeOperations * string * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListNextOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.ListNextAsync (operations, nextPageLink, computeNodeListNextOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions/&lt;ListNextAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNode&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IComputeNodeOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="computeNodeListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeListNextOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="computeNodeListNextOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die Serverknoten in den angegebenen Pool.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Reboot">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootHeaders Reboot (this Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt; nodeRebootOption = null, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOptions computeNodeRebootOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootHeaders Reboot(class Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt; nodeRebootOption, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOptions computeNodeRebootOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.Reboot(Microsoft.Azure.Batch.Protocol.IComputeNodeOperations,System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption},Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOptions)" />
      <MemberSignature Language="F#" Value="static member Reboot : Microsoft.Azure.Batch.Protocol.IComputeNodeOperations * string * string * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt; * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootHeaders" Usage="Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.Reboot (operations, poolId, nodeId, nodeRebootOption, computeNodeRebootOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IComputeNodeOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="nodeRebootOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt;" />
        <Parameter Name="computeNodeRebootOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID des Serverknotens, die neu gestartet werden soll.
            </param>
        <param name="nodeRebootOption">
            Wann Serverknoten neu starten, und was mit den derzeit ausgeführten Tasks geschehen. Der Standardwert ist „requeue“. Folgende Werte sind möglich: "wieder in Warteschlange", "Beenden", "TaskCompletion", "RetainedData"
            </param>
        <param name="computeNodeRebootOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Startet die angegebene Serverknoten neu.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Sie können einen Knoten nur, wenn es in einem im Leerlauf befindlichen oder ausgeführten Zustand neu starten.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="RebootAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootHeaders&gt; RebootAsync (this Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt; nodeRebootOption = null, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOptions computeNodeRebootOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootHeaders&gt; RebootAsync(class Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt; nodeRebootOption, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOptions computeNodeRebootOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.RebootAsync(Microsoft.Azure.Batch.Protocol.IComputeNodeOperations,System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption},Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RebootAsync : Microsoft.Azure.Batch.Protocol.IComputeNodeOperations * string * string * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt; * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.RebootAsync (operations, poolId, nodeId, nodeRebootOption, computeNodeRebootOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions/&lt;RebootAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IComputeNodeOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="nodeRebootOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOption&gt;" />
        <Parameter Name="computeNodeRebootOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeRebootOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID des Serverknotens, die neu gestartet werden soll.
            </param>
        <param name="nodeRebootOption">
            Wann Serverknoten neu starten, und was mit den derzeit ausgeführten Tasks geschehen. Der Standardwert ist „requeue“. Folgende Werte sind möglich: "wieder in Warteschlange", "Beenden", "TaskCompletion", "RetainedData"
            </param>
        <param name="computeNodeRebootOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Startet die angegebene Serverknoten neu.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Sie können einen Knoten nur, wenn es in einem im Leerlauf befindlichen oder ausgeführten Zustand neu starten.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Reimage">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageHeaders Reimage (this Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt; nodeReimageOption = null, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOptions computeNodeReimageOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageHeaders Reimage(class Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt; nodeReimageOption, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOptions computeNodeReimageOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.Reimage(Microsoft.Azure.Batch.Protocol.IComputeNodeOperations,System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption},Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOptions)" />
      <MemberSignature Language="F#" Value="static member Reimage : Microsoft.Azure.Batch.Protocol.IComputeNodeOperations * string * string * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt; * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageHeaders" Usage="Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.Reimage (operations, poolId, nodeId, nodeReimageOption, computeNodeReimageOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IComputeNodeOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="nodeReimageOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt;" />
        <Parameter Name="computeNodeReimageOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID des Serverknotens, die neu gestartet werden soll.
            </param>
        <param name="nodeReimageOption">
            Wann reimaging dem Computeknoten und was mit den derzeit ausgeführten Tasks geschehen. Der Standardwert ist „requeue“. Folgende Werte sind möglich: "wieder in Warteschlange", "Beenden", "TaskCompletion", "RetainedData"
            </param>
        <param name="computeNodeReimageOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Neuinstallation des Betriebssystems auf den angegebenen Computeknoten.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Sie können das Betriebssystem auf einem Knoten neu installieren, nur dann, wenn es in einem im Leerlauf befindlichen oder ausgeführten Zustand befindet. Diese API kann nur auf mit der Cloud-Dienstkonfigurationseigenschaft erstellten Ressourcenpools aufgerufen werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ReimageAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageHeaders&gt; ReimageAsync (this Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt; nodeReimageOption = null, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOptions computeNodeReimageOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageHeaders&gt; ReimageAsync(class Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt; nodeReimageOption, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOptions computeNodeReimageOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.ReimageAsync(Microsoft.Azure.Batch.Protocol.IComputeNodeOperations,System.String,System.String,System.Nullable{Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption},Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ReimageAsync : Microsoft.Azure.Batch.Protocol.IComputeNodeOperations * string * string * Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt; * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.ReimageAsync (operations, poolId, nodeId, nodeReimageOption, computeNodeReimageOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions/&lt;ReimageAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IComputeNodeOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="nodeReimageOption" Type="System.Nullable&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOption&gt;" />
        <Parameter Name="computeNodeReimageOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeReimageOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID des Serverknotens, die neu gestartet werden soll.
            </param>
        <param name="nodeReimageOption">
            Wann reimaging dem Computeknoten und was mit den derzeit ausgeführten Tasks geschehen. Der Standardwert ist „requeue“. Folgende Werte sind möglich: "wieder in Warteschlange", "Beenden", "TaskCompletion", "RetainedData"
            </param>
        <param name="computeNodeReimageOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Neuinstallation des Betriebssystems auf den angegebenen Computeknoten.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Sie können das Betriebssystem auf einem Knoten neu installieren, nur dann, wenn es in einem im Leerlauf befindlichen oder ausgeführten Zustand befindet. Diese API kann nur auf mit der Cloud-Dienstkonfigurationseigenschaft erstellten Ressourcenpools aufgerufen werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateUser">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserHeaders UpdateUser (this Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, string userName, Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter nodeUpdateUserParameter, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserOptions computeNodeUpdateUserOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserHeaders UpdateUser(class Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, string userName, class Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter nodeUpdateUserParameter, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserOptions computeNodeUpdateUserOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.UpdateUser(Microsoft.Azure.Batch.Protocol.IComputeNodeOperations,System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserOptions)" />
      <MemberSignature Language="F#" Value="static member UpdateUser : Microsoft.Azure.Batch.Protocol.IComputeNodeOperations * string * string * string * Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserHeaders" Usage="Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.UpdateUser (operations, poolId, nodeId, userName, nodeUpdateUserParameter, computeNodeUpdateUserOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IComputeNodeOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="nodeUpdateUserParameter" Type="Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter" />
        <Parameter Name="computeNodeUpdateUserOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID des Computers, auf dem Sie ein Benutzerkonto aktualisieren möchten.
            </param>
        <param name="userName">
            Der Name des Benutzerkontos aktualisieren.
            </param>
        <param name="nodeUpdateUserParameter">
            Die Parameter für die Anforderung.
            </param>
        <param name="computeNodeUpdateUserOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Aktualisiert das Kennwort und eine Ablaufzeit Zeit eines Benutzerkontos auf den angegebenen Computeknoten.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Dieser Vorgang ersetzt alle aktualisierbaren Eigenschaften des Kontos.
            Wenn ExpiryTime-Element nicht angegeben ist, wird der aktuelle Wert z. B. mit dem Standardwert nicht links unverändert bleiben sollen ersetzt. Sie können ein Benutzerkonto auf einem Knoten aktualisieren, nur, wenn sie den Status im Leerlauf befindet oder ausgeführt wird.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateUserAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserHeaders&gt; UpdateUserAsync (this Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, string userName, Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter nodeUpdateUserParameter, Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserOptions computeNodeUpdateUserOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserHeaders&gt; UpdateUserAsync(class Microsoft.Azure.Batch.Protocol.IComputeNodeOperations operations, string poolId, string nodeId, string userName, class Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter nodeUpdateUserParameter, class Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserOptions computeNodeUpdateUserOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.UpdateUserAsync(Microsoft.Azure.Batch.Protocol.IComputeNodeOperations,System.String,System.String,System.String,Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter,Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateUserAsync : Microsoft.Azure.Batch.Protocol.IComputeNodeOperations * string * string * string * Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter * Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions.UpdateUserAsync (operations, poolId, nodeId, userName, nodeUpdateUserParameter, computeNodeUpdateUserOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.ComputeNodeOperationsExtensions/&lt;UpdateUserAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IComputeNodeOperations" RefType="this" />
        <Parameter Name="poolId" Type="System.String" />
        <Parameter Name="nodeId" Type="System.String" />
        <Parameter Name="userName" Type="System.String" />
        <Parameter Name="nodeUpdateUserParameter" Type="Microsoft.Azure.Batch.Protocol.Models.NodeUpdateUserParameter" />
        <Parameter Name="computeNodeUpdateUserOptions" Type="Microsoft.Azure.Batch.Protocol.Models.ComputeNodeUpdateUserOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="poolId">
            Die ID des Pools, den Compute-Knoten enthält.
            </param>
        <param name="nodeId">
            Die ID des Computers, auf dem Sie ein Benutzerkonto aktualisieren möchten.
            </param>
        <param name="userName">
            Der Name des Benutzerkontos aktualisieren.
            </param>
        <param name="nodeUpdateUserParameter">
            Die Parameter für die Anforderung.
            </param>
        <param name="computeNodeUpdateUserOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert das Kennwort und eine Ablaufzeit Zeit eines Benutzerkontos auf den angegebenen Computeknoten.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Dieser Vorgang ersetzt alle aktualisierbaren Eigenschaften des Kontos.
            Wenn ExpiryTime-Element nicht angegeben ist, wird der aktuelle Wert z. B. mit dem Standardwert nicht links unverändert bleiben sollen ersetzt. Sie können ein Benutzerkonto auf einem Knoten aktualisieren, nur, wenn sie den Status im Leerlauf befindet oder ausgeführt wird.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>