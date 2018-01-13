<Type Name="VirtualMachinesOperationsExtensions" FullName="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class VirtualMachinesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit VirtualMachinesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module VirtualMachinesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type VirtualMachinesOperationsExtensions = class" />
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
            Erweiterungsmethoden für VirtualMachinesOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCapture">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult BeginCapture (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult BeginCapture(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginCapture(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCapture (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String, parameters As VirtualMachineCaptureParameters) As VirtualMachineCaptureResult" />
      <MemberSignature Language="F#" Value="static member BeginCapture : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginCapture (operations, resourceGroupName, vmName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers.
            </param>
        <param name="parameters">
            Parameter für den virtuellen Computer aufzeichnen zur Verfügung gestellt.
            </param>
        <summary>
            Erfasst den virtuellen Computer durch Kopieren virtueller Festplatten des virtuellen Computers, und gibt eine Vorlage, die zum Erstellen von ähnlichen virtuellen Computern verwendet werden kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCaptureAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult&gt; BeginCaptureAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult&gt; BeginCaptureAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginCaptureAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCaptureAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginCaptureAsync (operations, resourceGroupName, vmName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;BeginCaptureAsync&gt;d__35))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters" />
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
            Der Name des virtuellen Computers.
            </param>
        <param name="parameters">
            Parameter für den virtuellen Computer aufzeichnen zur Verfügung gestellt.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erfasst den virtuellen Computer durch Kopieren virtueller Festplatten des virtuellen Computers, und gibt eine Vorlage, die zum Erstellen von ähnlichen virtuellen Computern verwendet werden kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginConvertToManagedDisks">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginConvertToManagedDisks (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginConvertToManagedDisks(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginConvertToManagedDisks(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginConvertToManagedDisks (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginConvertToManagedDisks : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginConvertToManagedDisks (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers.
            </param>
        <summary>
            Konvertiert Datenträger der virtuellen Maschine von Blob-basierten verwalteten Datenträger an. Virtuelle Maschine muss beendet dessen Zuordnung aufgehoben werden, vor dem Aufrufen dieser Vorgang wird.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginConvertToManagedDisksAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginConvertToManagedDisksAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginConvertToManagedDisksAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginConvertToManagedDisksAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginConvertToManagedDisksAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginConvertToManagedDisksAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;BeginConvertToManagedDisksAsync&gt;d__41))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
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
            Der Name des virtuellen Computers.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Konvertiert Datenträger der virtuellen Maschine von Blob-basierten verwalteten Datenträger an. Virtuelle Maschine muss beendet dessen Zuordnung aufgehoben werden, vor dem Aufrufen dieser Vorgang wird.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.VirtualMachine BeginCreateOrUpdate (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Models.VirtualMachine parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.VirtualMachine BeginCreateOrUpdate(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Models.VirtualMachine parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginCreateOrUpdate(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachine)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreateOrUpdate (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String, parameters As VirtualMachine) As VirtualMachine" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdate : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachine -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachine" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginCreateOrUpdate (operations, resourceGroupName, vmName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachine</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachine" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers.
            </param>
        <param name="parameters">
            Parameter für das Erstellen virtueller Computer zur Verfügung gestellt.
            </param>
        <summary>
            Der Vorgang zum Erstellen oder Aktualisieren eines virtuellen Computers.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt; BeginCreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Models.VirtualMachine parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt; BeginCreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Models.VirtualMachine parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginCreateOrUpdateAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachine,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateOrUpdateAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachine * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginCreateOrUpdateAsync (operations, resourceGroupName, vmName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;BeginCreateOrUpdateAsync&gt;d__37))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachine" />
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
            Der Name des virtuellen Computers.
            </param>
        <param name="parameters">
            Parameter für das Erstellen virtueller Computer zur Verfügung gestellt.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Der Vorgang zum Erstellen oder Aktualisieren eines virtuellen Computers.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeallocate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginDeallocate (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginDeallocate(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginDeallocate(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDeallocate (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginDeallocate : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginDeallocate (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers.
            </param>
        <summary>
            Der virtuelle Computer heruntergefahren, und die Serverressourcen freigegeben. Sie sind nicht für die Serverressourcen in Rechnung gestellt, die dieser virtuellen Maschine verwendet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeallocateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginDeallocateAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginDeallocateAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginDeallocateAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeallocateAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginDeallocateAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;BeginDeallocateAsync&gt;d__43))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
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
            Der Name des virtuellen Computers.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Der virtuelle Computer heruntergefahren, und die Serverressourcen freigegeben. Sie sind nicht für die Serverressourcen in Rechnung gestellt, die dieser virtuellen Maschine verwendet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginDelete (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginDelete(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginDelete(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginDelete (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginDelete (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers.
            </param>
        <summary>
            Der Vorgang zum Löschen einer virtuellen Maschine.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginDeleteAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginDeleteAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginDeleteAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;BeginDeleteAsync&gt;d__39))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
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
            Der Name des virtuellen Computers.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Der Vorgang zum Löschen einer virtuellen Maschine.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPerformMaintenance">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginPerformMaintenance (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginPerformMaintenance(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginPerformMaintenance(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginPerformMaintenance (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginPerformMaintenance : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginPerformMaintenance (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers.
            </param>
        <summary>
            Der Vorgang für die Wartungsarbeiten auf einem virtuellen Computer.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPerformMaintenanceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginPerformMaintenanceAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginPerformMaintenanceAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginPerformMaintenanceAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginPerformMaintenanceAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginPerformMaintenanceAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;BeginPerformMaintenanceAsync&gt;d__53))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
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
            Der Name des virtuellen Computers.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Der Vorgang für die Wartungsarbeiten auf einem virtuellen Computer.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPowerOff">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginPowerOff (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginPowerOff(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginPowerOff(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginPowerOff (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginPowerOff : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginPowerOff (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers.
            </param>
        <summary>
            Der Vorgang (Beenden) eine virtuelle Maschine ausgeschaltet werden soll. Die virtuelle Maschine kann mit den gleichen bereitgestellten Ressourcen neu gestartet werden. Sie werden immer noch für diesen virtuellen Computer in Rechnung gestellt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginPowerOffAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginPowerOffAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginPowerOffAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginPowerOffAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginPowerOffAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginPowerOffAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;BeginPowerOffAsync&gt;d__45))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
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
            Der Name des virtuellen Computers.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Der Vorgang (Beenden) eine virtuelle Maschine ausgeschaltet werden soll. Die virtuelle Maschine kann mit den gleichen bereitgestellten Ressourcen neu gestartet werden. Sie werden immer noch für diesen virtuellen Computer in Rechnung gestellt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRedeploy">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginRedeploy (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginRedeploy(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginRedeploy(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginRedeploy (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginRedeploy : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginRedeploy (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers.
            </param>
        <summary>
            Der Vorgang auf einen virtuellen Computer erneut bereitzustellen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRedeployAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginRedeployAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginRedeployAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginRedeployAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginRedeployAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginRedeployAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;BeginRedeployAsync&gt;d__51))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
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
            Der Name des virtuellen Computers.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Der Vorgang auf einen virtuellen Computer erneut bereitzustellen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRestart">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginRestart (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginRestart(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginRestart(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginRestart (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginRestart : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginRestart (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers.
            </param>
        <summary>
            Der Vorgang zum Neustart eines virtuellen Computers.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRestartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginRestartAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginRestartAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginRestartAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginRestartAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginRestartAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;BeginRestartAsync&gt;d__47))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
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
            Der Name des virtuellen Computers.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Der Vorgang zum Neustart eines virtuellen Computers.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRunCommand">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.RunCommandResult BeginRunCommand (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Models.RunCommandInput parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.RunCommandResult BeginRunCommand(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Models.RunCommandInput parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginRunCommand(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.RunCommandInput)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginRunCommand (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String, parameters As RunCommandInput) As RunCommandResult" />
      <MemberSignature Language="F#" Value="static member BeginRunCommand : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * Microsoft.Azure.Management.Compute.Models.RunCommandInput -&gt; Microsoft.Azure.Management.Compute.Models.RunCommandResult" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginRunCommand (operations, resourceGroupName, vmName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.RunCommandResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.RunCommandInput" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers.
            </param>
        <param name="parameters">
            Um den Vorgang "ausführen"-Befehl angegebenen Parametern.
            </param>
        <summary>
            Befehl auf dem virtuellen Computer ausführen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginRunCommandAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.RunCommandResult&gt; BeginRunCommandAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Models.RunCommandInput parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.RunCommandResult&gt; BeginRunCommandAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Models.RunCommandInput parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginRunCommandAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.RunCommandInput,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginRunCommandAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * Microsoft.Azure.Management.Compute.Models.RunCommandInput * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.RunCommandResult&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginRunCommandAsync (operations, resourceGroupName, vmName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;BeginRunCommandAsync&gt;d__55))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.RunCommandResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.RunCommandInput" />
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
            Der Name des virtuellen Computers.
            </param>
        <param name="parameters">
            Um den Vorgang "ausführen"-Befehl angegebenen Parametern.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Befehl auf dem virtuellen Computer ausführen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStart">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginStart (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse BeginStart(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginStart(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginStart (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member BeginStart : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginStart (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers.
            </param>
        <summary>
            Der Vorgang zum Starten einer virtuellen Maschine.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginStartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginStartAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; BeginStartAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginStartAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginStartAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.BeginStartAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;BeginStartAsync&gt;d__49))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
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
            Der Name des virtuellen Computers.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Der Vorgang zum Starten einer virtuellen Maschine.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Capture">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult Capture (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult Capture(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Capture(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Capture (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String, parameters As VirtualMachineCaptureParameters) As VirtualMachineCaptureResult" />
      <MemberSignature Language="F#" Value="static member Capture : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Capture (operations, resourceGroupName, vmName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers.
            </param>
        <param name="parameters">
            Parameter für den virtuellen Computer aufzeichnen zur Verfügung gestellt.
            </param>
        <summary>
            Erfasst den virtuellen Computer durch Kopieren virtueller Festplatten des virtuellen Computers, und gibt eine Vorlage, die zum Erstellen von ähnlichen virtuellen Computern verwendet werden kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CaptureAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult&gt; CaptureAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult&gt; CaptureAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.CaptureAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CaptureAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.CaptureAsync (operations, resourceGroupName, vmName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;CaptureAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters" />
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
            Der Name des virtuellen Computers.
            </param>
        <param name="parameters">
            Parameter für den virtuellen Computer aufzeichnen zur Verfügung gestellt.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Erfasst den virtuellen Computer durch Kopieren virtueller Festplatten des virtuellen Computers, und gibt eine Vorlage, die zum Erstellen von ähnlichen virtuellen Computern verwendet werden kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConvertToManagedDisks">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse ConvertToManagedDisks (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse ConvertToManagedDisks(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ConvertToManagedDisks(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ConvertToManagedDisks (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member ConvertToManagedDisks : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ConvertToManagedDisks (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers.
            </param>
        <summary>
            Konvertiert Datenträger der virtuellen Maschine von Blob-basierten verwalteten Datenträger an. Virtuelle Maschine muss beendet dessen Zuordnung aufgehoben werden, vor dem Aufrufen dieser Vorgang wird.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConvertToManagedDisksAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; ConvertToManagedDisksAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; ConvertToManagedDisksAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ConvertToManagedDisksAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ConvertToManagedDisksAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ConvertToManagedDisksAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;ConvertToManagedDisksAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
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
            Der Name des virtuellen Computers.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Konvertiert Datenträger der virtuellen Maschine von Blob-basierten verwalteten Datenträger an. Virtuelle Maschine muss beendet dessen Zuordnung aufgehoben werden, vor dem Aufrufen dieser Vorgang wird.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.VirtualMachine CreateOrUpdate (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Models.VirtualMachine parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.VirtualMachine CreateOrUpdate(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Models.VirtualMachine parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.CreateOrUpdate(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachine)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function CreateOrUpdate (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String, parameters As VirtualMachine) As VirtualMachine" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdate : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachine -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachine" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.CreateOrUpdate (operations, resourceGroupName, vmName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachine</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachine" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers.
            </param>
        <param name="parameters">
            Parameter für das Erstellen virtueller Computer zur Verfügung gestellt.
            </param>
        <summary>
            Der Vorgang zum Erstellen oder Aktualisieren eines virtuellen Computers.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateOrUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt; CreateOrUpdateAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Models.VirtualMachine parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt; CreateOrUpdateAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Models.VirtualMachine parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.CreateOrUpdateAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachine,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateOrUpdateAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * Microsoft.Azure.Management.Compute.Models.VirtualMachine * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.CreateOrUpdateAsync (operations, resourceGroupName, vmName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;CreateOrUpdateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.VirtualMachine" />
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
            Der Name des virtuellen Computers.
            </param>
        <param name="parameters">
            Parameter für das Erstellen virtueller Computer zur Verfügung gestellt.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Der Vorgang zum Erstellen oder Aktualisieren eines virtuellen Computers.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Deallocate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Deallocate (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Deallocate(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Deallocate(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Deallocate (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member Deallocate : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Deallocate (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers.
            </param>
        <summary>
            Der virtuelle Computer heruntergefahren, und die Serverressourcen freigegeben. Sie sind nicht für die Serverressourcen in Rechnung gestellt, die dieser virtuellen Maschine verwendet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeallocateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeallocateAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeallocateAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.DeallocateAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeallocateAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.DeallocateAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;DeallocateAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
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
            Der Name des virtuellen Computers.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Der virtuelle Computer heruntergefahren, und die Serverressourcen freigegeben. Sie sind nicht für die Serverressourcen in Rechnung gestellt, die dieser virtuellen Maschine verwendet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Delete (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Delete(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Delete(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Delete (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Delete (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers.
            </param>
        <summary>
            Der Vorgang zum Löschen einer virtuellen Maschine.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeleteAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; DeleteAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.DeleteAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
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
            Der Name des virtuellen Computers.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Der Vorgang zum Löschen einer virtuellen Maschine.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Generalize">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Generalize (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Generalize(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Generalize(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Generalize (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member Generalize : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Generalize (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers.
            </param>
        <summary>
            Legt den Zustand des virtuellen Computers zu generalisiert.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GeneralizeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; GeneralizeAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; GeneralizeAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.GeneralizeAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GeneralizeAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.GeneralizeAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;GeneralizeAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
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
            Der Name des virtuellen Computers.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Legt den Zustand des virtuellen Computers zu generalisiert.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.VirtualMachine Get (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Nullable&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewTypes&gt; expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.VirtualMachine Get(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.InstanceViewTypes&gt; expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Get(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Nullable{Microsoft.Azure.Management.Compute.Models.InstanceViewTypes})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String, Optional expand As Nullable(Of InstanceViewTypes) = null) As VirtualMachine" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * Nullable&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewTypes&gt; -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachine" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Get (operations, resourceGroupName, vmName, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachine</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="expand" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewTypes&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers.
            </param>
        <param name="expand">
            Der erweitern-Ausdruck auf die Operation angewendet werden soll. Folgende Werte sind möglich: "" InstanceView"
            </param>
        <summary>
            Ruft Informationen über die Modell- oder Instanzansicht eines virtuellen Computers ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt; GetAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Nullable&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewTypes&gt; expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt; GetAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.Compute.Models.InstanceViewTypes&gt; expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.GetAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Nullable{Microsoft.Azure.Management.Compute.Models.InstanceViewTypes},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * Nullable&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewTypes&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.GetAsync (operations, resourceGroupName, vmName, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="expand" Type="System.Nullable&lt;Microsoft.Azure.Management.Compute.Models.InstanceViewTypes&gt;" />
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
            Der Name des virtuellen Computers.
            </param>
        <param name="expand">
            Der erweitern-Ausdruck auf die Operation angewendet werden soll. Folgende Werte sind möglich: "" InstanceView"
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Informationen über die Modell- oder Instanzansicht eines virtuellen Computers ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceView">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView InstanceView (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView InstanceView(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.InstanceView(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function InstanceView (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As VirtualMachineInstanceView" />
      <MemberSignature Language="F#" Value="static member InstanceView : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.InstanceView (operations, resourceGroupName, vmName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers.
            </param>
        <summary>
            Ruft Informationen über den Laufzeitzustand eines virtuellen Computers ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="InstanceViewAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView&gt; InstanceViewAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView&gt; InstanceViewAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.InstanceViewAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member InstanceViewAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.InstanceViewAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;InstanceViewAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineInstanceView&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
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
            Der Name des virtuellen Computers.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Informationen über den Laufzeitzustand eines virtuellen Computers ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt; List (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt; List(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.List(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IVirtualMachinesOperations, resourceGroupName As String) As IPage(Of VirtualMachine)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.List (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <summary>
            Zeigt eine Liste aller virtuellen Computer in der angegebenen Ressourcengruppe. Verwenden Sie die Eigenschaft "NextLink" in der Antwort, um die nächste Seite von virtuellen Computern abzurufen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAll">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt; ListAll (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt; ListAll(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListAll(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAll (operations As IVirtualMachinesOperations) As IPage(Of VirtualMachine)" />
      <MemberSignature Language="F#" Value="static member ListAll : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListAll operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <summary>
            Zeigt eine Liste aller virtuellen Computer in das angegebene Abonnement. Verwenden Sie die Eigenschaft "NextLink" in der Antwort, um die nächste Seite von virtuellen Computern abzurufen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt; ListAllAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt; ListAllAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListAllAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListAllAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;ListAllAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zeigt eine Liste aller virtuellen Computer in das angegebene Abonnement. Verwenden Sie die Eigenschaft "NextLink" in der Antwort, um die nächste Seite von virtuellen Computern abzurufen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt; ListAllNext (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt; ListAllNext(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListAllNext(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAllNext (operations As IVirtualMachinesOperations, nextPageLink As String) As IPage(Of VirtualMachine)" />
      <MemberSignature Language="F#" Value="static member ListAllNext : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListAllNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <summary>
            Zeigt eine Liste aller virtuellen Computer in das angegebene Abonnement. Verwenden Sie die Eigenschaft "NextLink" in der Antwort, um die nächste Seite von virtuellen Computern abzurufen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAllNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt; ListAllNextAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt; ListAllNextAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListAllNextAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAllNextAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListAllNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;ListAllNextAsync&gt;d__59))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zeigt eine Liste aller virtuellen Computer in das angegebene Abonnement. Verwenden Sie die Eigenschaft "NextLink" in der Antwort, um die nächste Seite von virtuellen Computern abzurufen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt; ListAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt; ListAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;ListAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zeigt eine Liste aller virtuellen Computer in der angegebenen Ressourcengruppe. Verwenden Sie die Eigenschaft "NextLink" in der Antwort, um die nächste Seite von virtuellen Computern abzurufen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableSizes">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt; ListAvailableSizes (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt; ListAvailableSizes(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListAvailableSizes(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListAvailableSizes (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As IEnumerable(Of VirtualMachineSize)" />
      <MemberSignature Language="F#" Value="static member ListAvailableSizes : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListAvailableSizes (operations, resourceGroupName, vmName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers.
            </param>
        <summary>
            Listet alle verfügbaren VM-Größen, die den angegebenen virtuellen Computer auf die Größe geändert werden kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableSizesAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;&gt; ListAvailableSizesAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;&gt; ListAvailableSizesAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListAvailableSizesAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAvailableSizesAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListAvailableSizesAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;ListAvailableSizesAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachineSize&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
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
            Der Name des virtuellen Computers.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet alle verfügbaren VM-Größen, die den angegebenen virtuellen Computer auf die Größe geändert werden kann.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt; ListNext (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt; ListNext(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListNext(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IVirtualMachinesOperations, nextPageLink As String) As IPage(Of VirtualMachine)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <summary>
            Zeigt eine Liste aller virtuellen Computer in der angegebenen Ressourcengruppe. Verwenden Sie die Eigenschaft "NextLink" in der Antwort, um die nächste Seite von virtuellen Computern abzurufen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;ListNextAsync&gt;d__57))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Compute.Models.VirtualMachine&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zeigt eine Liste aller virtuellen Computer in der angegebenen Ressourcengruppe. Verwenden Sie die Eigenschaft "NextLink" in der Antwort, um die nächste Seite von virtuellen Computern abzurufen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PerformMaintenance">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse PerformMaintenance (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse PerformMaintenance(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.PerformMaintenance(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PerformMaintenance (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member PerformMaintenance : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.PerformMaintenance (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers.
            </param>
        <summary>
            Der Vorgang für die Wartungsarbeiten auf einem virtuellen Computer.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PerformMaintenanceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; PerformMaintenanceAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; PerformMaintenanceAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.PerformMaintenanceAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PerformMaintenanceAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.PerformMaintenanceAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;PerformMaintenanceAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
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
            Der Name des virtuellen Computers.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Der Vorgang für die Wartungsarbeiten auf einem virtuellen Computer.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PowerOff">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse PowerOff (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse PowerOff(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.PowerOff(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function PowerOff (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member PowerOff : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.PowerOff (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers.
            </param>
        <summary>
            Der Vorgang (Beenden) eine virtuelle Maschine ausgeschaltet werden soll. Die virtuelle Maschine kann mit den gleichen bereitgestellten Ressourcen neu gestartet werden. Sie werden immer noch für diesen virtuellen Computer in Rechnung gestellt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PowerOffAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; PowerOffAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; PowerOffAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.PowerOffAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PowerOffAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.PowerOffAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;PowerOffAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
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
            Der Name des virtuellen Computers.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Der Vorgang (Beenden) eine virtuelle Maschine ausgeschaltet werden soll. Die virtuelle Maschine kann mit den gleichen bereitgestellten Ressourcen neu gestartet werden. Sie werden immer noch für diesen virtuellen Computer in Rechnung gestellt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Redeploy">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Redeploy (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Redeploy(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Redeploy(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Redeploy (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member Redeploy : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Redeploy (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers.
            </param>
        <summary>
            Der Vorgang auf einen virtuellen Computer erneut bereitzustellen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RedeployAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; RedeployAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; RedeployAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.RedeployAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RedeployAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.RedeployAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;RedeployAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
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
            Der Name des virtuellen Computers.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Der Vorgang auf einen virtuellen Computer erneut bereitzustellen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Restart">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Restart (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Restart(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Restart(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Restart (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member Restart : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Restart (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers.
            </param>
        <summary>
            Der Vorgang zum Neustart eines virtuellen Computers.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; RestartAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; RestartAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.RestartAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RestartAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.RestartAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;RestartAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
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
            Der Name des virtuellen Computers.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Der Vorgang zum Neustart eines virtuellen Computers.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunCommand">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.RunCommandResult RunCommand (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Models.RunCommandInput parameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.RunCommandResult RunCommand(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Models.RunCommandInput parameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.RunCommand(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.RunCommandInput)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function RunCommand (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String, parameters As RunCommandInput) As RunCommandResult" />
      <MemberSignature Language="F#" Value="static member RunCommand : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * Microsoft.Azure.Management.Compute.Models.RunCommandInput -&gt; Microsoft.Azure.Management.Compute.Models.RunCommandResult" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.RunCommand (operations, resourceGroupName, vmName, parameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Models.RunCommandResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.RunCommandInput" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers.
            </param>
        <param name="parameters">
            Um den Vorgang "ausführen"-Befehl angegebenen Parametern.
            </param>
        <summary>
            Befehl auf dem virtuellen Computer ausführen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RunCommandAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.RunCommandResult&gt; RunCommandAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, Microsoft.Azure.Management.Compute.Models.RunCommandInput parameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.RunCommandResult&gt; RunCommandAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, class Microsoft.Azure.Management.Compute.Models.RunCommandInput parameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.RunCommandAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.RunCommandInput,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RunCommandAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * Microsoft.Azure.Management.Compute.Models.RunCommandInput * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.RunCommandResult&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.RunCommandAsync (operations, resourceGroupName, vmName, parameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;RunCommandAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.RunCommandResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
        <Parameter Name="parameters" Type="Microsoft.Azure.Management.Compute.Models.RunCommandInput" />
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
            Der Name des virtuellen Computers.
            </param>
        <param name="parameters">
            Um den Vorgang "ausführen"-Befehl angegebenen Parametern.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Befehl auf dem virtuellen Computer ausführen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Start (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse Start(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Start(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Start (operations As IVirtualMachinesOperations, resourceGroupName As String, vmName As String) As OperationStatusResponse" />
      <MemberSignature Language="F#" Value="static member Start : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string -&gt; Microsoft.Azure.Management.Compute.Models.OperationStatusResponse" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Start (operations, resourceGroupName, vmName)" />
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
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe.
            </param>
        <param name="vmName">
            Der Name des virtuellen Computers.
            </param>
        <summary>
            Der Vorgang zum Starten einer virtuellen Maschine.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; StartAsync (this Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt; StartAsync(class Microsoft.Azure.Management.Compute.IVirtualMachinesOperations operations, string resourceGroupName, string vmName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.StartAsync(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member StartAsync : Microsoft.Azure.Management.Compute.IVirtualMachinesOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;" Usage="Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.StartAsync (operations, resourceGroupName, vmName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute</AssemblyName>
        <AssemblyVersion>16.0.0.0</AssemblyVersion>
        <AssemblyVersion>17.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions/&lt;StartAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Compute.Models.OperationStatusResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Compute.IVirtualMachinesOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="vmName" Type="System.String" />
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
            Der Name des virtuellen Computers.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Der Vorgang zum Starten einer virtuellen Maschine.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>