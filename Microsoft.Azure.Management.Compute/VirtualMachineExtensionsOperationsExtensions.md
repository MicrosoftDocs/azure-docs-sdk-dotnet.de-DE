<Type Name="VirtualMachineExtensionsOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualMachineExtensionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualMachineExtensionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualMachineExtensionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualMachineExtensionsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
    <AssemblyVersion>16.0.0.0</AssemblyVersion>
    <AssemblyVersion>17.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für VirtualMachineExtensionsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension BeginCreateOrUpdate (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension extensionParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension BeginCreateOrUpdate(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension extensionParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IVirtualMachineExtensionsOperations, resourceGroupName As String, vmName As String, vmExtensionName As String, extensionParameters As VirtualMachineExtension) As VirtualMachineExtension" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations * string * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, vmName, vmExtensionName, extensionParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="vmExtensionName" Type="System.String" />
        <Parameter Name="extensionParameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers, auf dem die Erweiterung verwendet werden soll, erstellen oder aktualisiert.
            </param>
        <param name="vmExtensionName">
            Der Name der Erweiterung des virtuellen Computers.
            </param>
        <param name="extensionParameters">
            Parameter für die Erweiterung zum Erstellen eines virtuellen Computers zur Verfügung gestellt.
            </param>
        <summary>
            Der Vorgang zum Erstellen oder aktualisieren Sie die Erweiterung.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension extensionParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension extensionParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations * string * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, vmName, vmExtensionName, extensionParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="vmExtensionName" Type="System.String" />
        <Parameter Name="extensionParameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers, auf dem die Erweiterung verwendet werden soll, erstellen oder aktualisiert.
            </param>
        <param name="vmExtensionName">
            Der Name der Erweiterung des virtuellen Computers.
            </param>
        <param name="extensionParameters">
            Parameter für die Erweiterung zum Erstellen eines virtuellen Computers zur Verfügung gestellt.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Der Vorgang zum Erstellen oder aktualisieren Sie die Erweiterung.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginDelete (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginDelete(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As IVirtualMachineExtensionsOperations, resourceGroupName As String, vmName As String, vmExtensionName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.BeginDelete (operations, resourceGroupName, vmName, vmExtensionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="vmExtensionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers, auf dem die Erweiterung gelöscht werden soll.
            </param>
        <param name="vmExtensionName">
            Der Name der Erweiterung des virtuellen Computers.
            </param>
        <summary>
            Der Vorgang zum Löschen der Erweiterungs.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, vmName, vmExtensionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="vmExtensionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers, auf dem die Erweiterung gelöscht werden soll.
            </param>
        <param name="vmExtensionName">
            Der Name der Erweiterung des virtuellen Computers.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Der Vorgang zum Löschen der Erweiterungs.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension CreateOrUpdate (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension extensionParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension CreateOrUpdate(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension extensionParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IVirtualMachineExtensionsOperations, resourceGroupName As String, vmName As String, vmExtensionName As String, extensionParameters As VirtualMachineExtension) As VirtualMachineExtension" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations * string * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, vmName, vmExtensionName, extensionParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="vmExtensionName" Type="System.String" />
        <Parameter Name="extensionParameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers, auf dem die Erweiterung verwendet werden soll, erstellen oder aktualisiert.
            </param>
        <param name="vmExtensionName">
            Der Name der Erweiterung des virtuellen Computers.
            </param>
        <param name="extensionParameters">
            Parameter für die Erweiterung zum Erstellen eines virtuellen Computers zur Verfügung gestellt.
            </param>
        <summary>
            Der Vorgang zum Erstellen oder aktualisieren Sie die Erweiterung.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension extensionParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension extensionParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations,System.String,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations * string * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, vmName, vmExtensionName, extensionParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="vmExtensionName" Type="System.String" />
        <Parameter Name="extensionParameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers, auf dem die Erweiterung verwendet werden soll, erstellen oder aktualisiert.
            </param>
        <param name="vmExtensionName">
            Der Name der Erweiterung des virtuellen Computers.
            </param>
        <param name="extensionParameters">
            Parameter für die Erweiterung zum Erstellen eines virtuellen Computers zur Verfügung gestellt.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Der Vorgang zum Erstellen oder aktualisieren Sie die Erweiterung.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Delete (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Delete(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.Delete(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IVirtualMachineExtensionsOperations, resourceGroupName As String, vmName As String, vmExtensionName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.Delete (operations, resourceGroupName, vmName, vmExtensionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.OperationStatusResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="vmExtensionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers, auf dem die Erweiterung gelöscht werden soll.
            </param>
        <param name="vmExtensionName">
            Der Name der Erweiterung des virtuellen Computers.
            </param>
        <summary>
            Der Vorgang zum Löschen der Erweiterungs.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.DeleteAsync (operations, resourceGroupName, vmName, vmExtensionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="vmExtensionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers, auf dem die Erweiterung gelöscht werden soll.
            </param>
        <param name="vmExtensionName">
            Der Name der Erweiterung des virtuellen Computers.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Der Vorgang zum Löschen der Erweiterungs.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension Get (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension Get(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.Get(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IVirtualMachineExtensionsOperations, resourceGroupName As String, vmName As String, vmExtensionName As String, Optional expand As String = null) As VirtualMachineExtension" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations * string * string * string * string -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.Get (operations, resourceGroupName, vmName, vmExtensionName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="vmExtensionName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers an, die die Erweiterung enthält.
            </param>
        <param name="vmExtensionName">
            Der Name der Erweiterung des virtuellen Computers.
            </param>
        <param name="expand">
            Der erweitern-Ausdruck auf die Operation angewendet werden soll.
            </param>
        <summary>
            Der Vorgang die Erweiterung abgerufen werden soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; GetAsync (this Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt; GetAsync(class Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations operations, string resourceGroupName, string vmName, string vmExtensionName, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions.GetAsync (operations, resourceGroupName, vmName, vmExtensionName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachineExtensionsOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineExtension&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachineExtensionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="vmExtensionName" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers an, die die Erweiterung enthält.
            </param>
        <param name="vmExtensionName">
            Der Name der Erweiterung des virtuellen Computers.
            </param>
        <param name="expand">
            Der erweitern-Ausdruck auf die Operation angewendet werden soll.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Der Vorgang die Erweiterung abgerufen werden soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>