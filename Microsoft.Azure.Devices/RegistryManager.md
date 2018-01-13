<Type Name="RegistryManager" FullName="Microsoft.Azure.Devices.RegistryManager">
  <TypeSignature Language="C#" Value="public abstract class RegistryManager : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit RegistryManager extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Devices.RegistryManager" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class RegistryManager&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type RegistryManager = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Enthält Methoden, die Dienste verwenden können, auszuführenden erstellen, entfernen, update und delete-Vorgänge auf Geräten.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected RegistryManager ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.#ctor" />
      <MemberSignature Language="VB.NET" Value="Protected Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt; AddDeviceAsync (Microsoft.Azure.Devices.Device device);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Device&gt; AddDeviceAsync(class Microsoft.Azure.Devices.Device device) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.AddDeviceAsync(Microsoft.Azure.Devices.Device)" />
      <MemberSignature Language="F#" Value="abstract member AddDeviceAsync : Microsoft.Azure.Devices.Device -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;" Usage="registryManager.AddDeviceAsync device" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="device" Type="Microsoft.Azure.Devices.Device" />
      </Parameters>
      <Docs>
        <param name="device">
            Das Objekt registriert werden.
            </param>
        <summary>
            Registrieren Sie ein neues Gerät mit dem system
            </summary>
        <returns>wiederholt zurück, das Objekt mit dem generierten Schlüsseln und etags</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt; AddDeviceAsync (Microsoft.Azure.Devices.Device device, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Device&gt; AddDeviceAsync(class Microsoft.Azure.Devices.Device device, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.AddDeviceAsync(Microsoft.Azure.Devices.Device,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddDeviceAsync : Microsoft.Azure.Devices.Device * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;" Usage="registryManager.AddDeviceAsync (device, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="device" Type="Microsoft.Azure.Devices.Device" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="device">
            Das Objekt registriert werden.
            </param>
        <param name="cancellationToken">
            Das Token, wodurch die der Vorgang abgebrochen werden.
            </param>
        <summary>
            Registrieren Sie ein neues Gerät mit dem system
            </summary>
        <returns>wiederholt zurück, das Objekt mit dem generierten Schlüsseln und etags</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddDevices2Async">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; AddDevices2Async (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; AddDevices2Async(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.AddDevices2Async(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function AddDevices2Async (devices As IEnumerable(Of Device)) As Task(Of BulkRegistryOperationResult)" />
      <MemberSignature Language="F#" Value="abstract member AddDevices2Async : seq&lt;Microsoft.Azure.Devices.Device&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;" Usage="registryManager.AddDevices2Async devices" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
      </Parameters>
      <Docs>
        <param name="devices">
            Geräteobjekte registriert werden.
            </param>
        <summary>
            Registrieren Sie eine Liste neuer Geräte mit dem system
            </summary>
        <returns>Gibt ein BulkRegistryOperationResult-Objekt</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddDevices2Async">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; AddDevices2Async (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; AddDevices2Async(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.AddDevices2Async(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddDevices2Async : seq&lt;Microsoft.Azure.Devices.Device&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;" Usage="registryManager.AddDevices2Async (devices, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="devices">
            Geräteobjekte registriert werden.
            </param>
        <param name="cancellationToken">
            Das Token, wodurch die der Vorgang abgebrochen werden.
            </param>
        <summary>
            Registrieren Sie eine Liste neuer Geräte mit dem system
            </summary>
        <returns>Gibt ein BulkRegistryOperationResult-Objekt</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;string[]&gt; AddDevicesAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string[]&gt; AddDevicesAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.AddDevicesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function AddDevicesAsync (devices As IEnumerable(Of Device)) As Task(Of String())" />
      <MemberSignature Language="F#" Value="abstract member AddDevicesAsync : seq&lt;Microsoft.Azure.Devices.Device&gt; -&gt; System.Threading.Tasks.Task&lt;string[]&gt;" Usage="registryManager.AddDevicesAsync devices" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use AddDevices2Async")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
      </Parameters>
      <Docs>
        <param name="devices">
            Geräteobjekte registriert werden.
            </param>
        <summary>
            Registrieren Sie eine Liste neuer Geräte mit dem system
            </summary>
        <returns>Gibt ein Zeichenfolgenarray von Fehlermeldungen zurück</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;string[]&gt; AddDevicesAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string[]&gt; AddDevicesAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.AddDevicesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member AddDevicesAsync : seq&lt;Microsoft.Azure.Devices.Device&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string[]&gt;" Usage="registryManager.AddDevicesAsync (devices, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use AddDevices2Async")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="devices">
            Geräteobjekte registriert werden.
            </param>
        <param name="cancellationToken">
            Das Token, wodurch die der Vorgang abgebrochen werden.
            </param>
        <summary>
            Registrieren Sie eine Liste neuer Geräte mit dem system
            </summary>
        <returns>Gibt ein Zeichenfolgenarray von Fehlermeldungen zurück</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelJobAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task CancelJobAsync (string jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CancelJobAsync(string jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.CancelJobAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CancelJobAsync (jobId As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member CancelJobAsync : string -&gt; System.Threading.Tasks.Task" Usage="registryManager.CancelJobAsync jobId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jobId">ID des Auftrags auf "Abbrechen"</param>
        <summary>
            Bricht/löscht den Auftrag mit der angegebenen ID.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancelJobAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task CancelJobAsync (string jobId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CancelJobAsync(string jobId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.CancelJobAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CancelJobAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="registryManager.CancelJobAsync (jobId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">ID des Auftrags auf "Abbrechen"</param>
        <param name="cancellationToken">Aufgabenabbruchtoken</param>
        <summary>
            Bricht/löscht den Auftrag mit der angegebenen ID.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task CloseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CloseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.CloseAsync" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CloseAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member CloseAsync : unit -&gt; System.Threading.Tasks.Task" Usage="registryManager.CloseAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Schließt die RegistryManager-Instanz, und seine Ressourcen frei.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateFromConnectionString">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Devices.RegistryManager CreateFromConnectionString (string connectionString);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Devices.RegistryManager CreateFromConnectionString(string connectionString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.CreateFromConnectionString(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CreateFromConnectionString (connectionString As String) As RegistryManager" />
      <MemberSignature Language="F#" Value="static member CreateFromConnectionString : string -&gt; Microsoft.Azure.Devices.RegistryManager" Usage="Microsoft.Azure.Devices.RegistryManager.CreateFromConnectionString connectionString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.RegistryManager</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="connectionString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="connectionString"> Der Iot Hub-Verbindungszeichenfolge.</param>
        <summary>
            Erstellt eine RegistryManager aus der Iot Hub-Verbindungszeichenfolge an.
            </summary>
        <returns> Eine RegistryManager-Instanz. </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQuery">
      <MemberSignature Language="C#" Value="public abstract Microsoft.Azure.Devices.IQuery CreateQuery (string sqlQueryString);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Devices.IQuery CreateQuery(string sqlQueryString) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.CreateQuery(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateQuery (sqlQueryString As String) As IQuery" />
      <MemberSignature Language="F#" Value="abstract member CreateQuery : string -&gt; Microsoft.Azure.Devices.IQuery" Usage="registryManager.CreateQuery sqlQueryString" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.IQuery</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sqlQueryString" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="sqlQueryString"></param>
        <summary>
            Ruft ein Handle, das über die ein Ergebnis für eine bestimmte Abfrage abgerufen werden kann.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQuery">
      <MemberSignature Language="C#" Value="public abstract Microsoft.Azure.Devices.IQuery CreateQuery (string sqlQueryString, Nullable&lt;int&gt; pageSize);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Devices.IQuery CreateQuery(string sqlQueryString, valuetype System.Nullable`1&lt;int32&gt; pageSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.CreateQuery(System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function CreateQuery (sqlQueryString As String, pageSize As Nullable(Of Integer)) As IQuery" />
      <MemberSignature Language="F#" Value="abstract member CreateQuery : string * Nullable&lt;int&gt; -&gt; Microsoft.Azure.Devices.IQuery" Usage="registryManager.CreateQuery (sqlQueryString, pageSize)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Devices.IQuery</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="sqlQueryString" Type="System.String" />
        <Parameter Name="pageSize" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="sqlQueryString"></param>
        <param name="pageSize"></param>
        <summary>
            Ruft ein Handle, das über die ein Ergebnis für eine bestimmte Abfrage abgerufen werden kann.
            </summary>
        <returns />
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="registryManager.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
        <inheritdoc />
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected virtual void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="abstract member Dispose : bool -&gt; unit&#xA;override this.Dispose : bool -&gt; unit" Usage="registryManager.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing">
          <c>"true"</c> um sowohl verwaltete als auch nicht verwaltete Ressourcen freizugeben <c>"false"</c> um ausschließlich nicht verwaltete Ressourcen freizugeben.</param>
        <summary>
            Nicht verwaltete und optional verwaltete Ressourcen frei.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt; ExportDevicesAsync (string exportBlobContainerUri, bool excludeKeys);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobProperties&gt; ExportDevicesAsync(string exportBlobContainerUri, bool excludeKeys) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ExportDevicesAsync(System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function ExportDevicesAsync (exportBlobContainerUri As String, excludeKeys As Boolean) As Task(Of JobProperties)" />
      <MemberSignature Language="F#" Value="abstract member ExportDevicesAsync : string * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;" Usage="registryManager.ExportDevicesAsync (exportBlobContainerUri, excludeKeys)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exportBlobContainerUri" Type="System.String" />
        <Parameter Name="excludeKeys" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="exportBlobContainerUri">Ziel-BLOB-Container-URI</param>
        <param name="excludeKeys">Gibt an, ob das Gerät Schlüssel während des Exports ausschließen</param>
        <summary>
            Erstellt einen neuen Bulk-Auftrag zum Exportieren von geräteregistrierungen in der mit dem bereitgestellten URI angegebenen Container.
            </summary>
        <returns>JobProperties des neu erstellten Auftrags.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt; ExportDevicesAsync (string exportBlobContainerUri, bool excludeKeys, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobProperties&gt; ExportDevicesAsync(string exportBlobContainerUri, bool excludeKeys, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ExportDevicesAsync(System.String,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExportDevicesAsync : string * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;" Usage="registryManager.ExportDevicesAsync (exportBlobContainerUri, excludeKeys, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exportBlobContainerUri" Type="System.String" />
        <Parameter Name="excludeKeys" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="exportBlobContainerUri">Ziel-BLOB-Container-URI</param>
        <param name="excludeKeys">Gibt an, ob das Gerät Schlüssel während des Exports ausschließen</param>
        <param name="cancellationToken">Aufgabenabbruchtoken</param>
        <summary>
            Erstellt einen neuen Bulk-Auftrag zum Exportieren von geräteregistrierungen in der mit dem bereitgestellten URI angegebenen Container.
            </summary>
        <returns>JobProperties des neu erstellten Auftrags.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt; ExportDevicesAsync (string exportBlobContainerUri, string outputBlobName, bool excludeKeys);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobProperties&gt; ExportDevicesAsync(string exportBlobContainerUri, string outputBlobName, bool excludeKeys) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ExportDevicesAsync(System.String,System.String,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function ExportDevicesAsync (exportBlobContainerUri As String, outputBlobName As String, excludeKeys As Boolean) As Task(Of JobProperties)" />
      <MemberSignature Language="F#" Value="abstract member ExportDevicesAsync : string * string * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;" Usage="registryManager.ExportDevicesAsync (exportBlobContainerUri, outputBlobName, excludeKeys)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exportBlobContainerUri" Type="System.String" />
        <Parameter Name="outputBlobName" Type="System.String" />
        <Parameter Name="excludeKeys" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="exportBlobContainerUri"></param>
        <param name="outputBlobName"></param>
        <param name="excludeKeys"></param>
        <summary>
            Erstellt einen neuen Bulk-Auftrag zum Exportieren von geräteregistrierungen in der mit dem bereitgestellten URI angegebenen Container.
            </summary>
        <returns>JobProperties des neu erstellten Auftrags.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExportDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt; ExportDevicesAsync (string exportBlobContainerUri, string outputBlobName, bool excludeKeys, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobProperties&gt; ExportDevicesAsync(string exportBlobContainerUri, string outputBlobName, bool excludeKeys, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ExportDevicesAsync(System.String,System.String,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExportDevicesAsync : string * string * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;" Usage="registryManager.ExportDevicesAsync (exportBlobContainerUri, outputBlobName, excludeKeys, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="exportBlobContainerUri" Type="System.String" />
        <Parameter Name="outputBlobName" Type="System.String" />
        <Parameter Name="excludeKeys" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="exportBlobContainerUri"></param>
        <param name="outputBlobName"></param>
        <param name="excludeKeys"></param>
        <param name="cancellationToken"></param>
        <summary>
            Erstellt einen neuen Bulk-Auftrag zum Exportieren von geräteregistrierungen in der mit dem bereitgestellten URI angegebenen Container.
            </summary>
        <returns>JobProperties des neu erstellten Auftrags.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt; GetDeviceAsync (string deviceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Device&gt; GetDeviceAsync(string deviceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetDeviceAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetDeviceAsync (deviceId As String) As Task(Of Device)" />
      <MemberSignature Language="F#" Value="abstract member GetDeviceAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;" Usage="registryManager.GetDeviceAsync deviceId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            Die Id des Geräts abgerufen werden sollen.
            </param>
        <summary>
            Ruft das angegebene Objekt ab.
            </summary>
        <returns>
            Das Gerät-Objekt.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt; GetDeviceAsync (string deviceId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Device&gt; GetDeviceAsync(string deviceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetDeviceAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDeviceAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;" Usage="registryManager.GetDeviceAsync (deviceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            Die Id des Geräts abgerufen werden sollen.
            </param>
        <param name="cancellationToken">
            Das Token, wodurch die der Vorgang abgebrochen werden.
            </param>
        <summary>
            Ruft das angegebene Objekt ab.
            </summary>
        <returns>
            Das Gerät-Objekt.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;&gt; GetDevicesAsync (int maxCount);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt;&gt; GetDevicesAsync(int32 maxCount) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetDevicesAsync(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetDevicesAsync (maxCount As Integer) As Task(Of IEnumerable(Of Device))" />
      <MemberSignature Language="F#" Value="abstract member GetDevicesAsync : int -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Devices.Device&gt;&gt;" Usage="registryManager.GetDevicesAsync maxCount" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxCount" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="maxCount">To be added.</param>
        <summary>
            Ruft die angegebene Anzahl von Geräten aus jeder Iot Hub-Partition. Dies ist eine Näherung darstellt und nicht auf eine endgültige Liste. Ergebnisse werden nicht sortiert.
            </summary>
        <returns>
            Die Liste der Geräte
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;&gt; GetDevicesAsync (int maxCount, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt;&gt; GetDevicesAsync(int32 maxCount, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetDevicesAsync(System.Int32,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDevicesAsync : int * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Devices.Device&gt;&gt;" Usage="registryManager.GetDevicesAsync (maxCount, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="maxCount" Type="System.Int32" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="maxCount">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Ruft die angegebene Anzahl von Geräten aus jeder Iot Hub-Partition. Dies ist eine Näherung darstellt und nicht auf eine endgültige Liste. Ergebnisse werden nicht sortiert.
            </summary>
        <returns>
            Die Liste der Geräte
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt; GetJobAsync (string jobId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobProperties&gt; GetJobAsync(string jobId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetJobAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetJobAsync (jobId As String) As Task(Of JobProperties)" />
      <MemberSignature Language="F#" Value="abstract member GetJobAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;" Usage="registryManager.GetJobAsync jobId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="jobId">Die ID des Objekts Auftrag abrufen</param>
        <summary>
            Ruft den Auftrag mit der angegebenen ID.
            </summary>
        <returns>JobProperties des Auftrags durch die bereitgestellten "JobID"-Wert angegeben.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt; GetJobAsync (string jobId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobProperties&gt; GetJobAsync(string jobId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetJobAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetJobAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;" Usage="registryManager.GetJobAsync (jobId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="jobId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="jobId">Die ID des Objekts Auftrag abrufen</param>
        <param name="cancellationToken">Aufgabenabbruchtoken</param>
        <summary>
            Ruft den Auftrag mit der angegebenen ID.
            </summary>
        <returns>JobProperties des Auftrags durch die bereitgestellten "JobID"-Wert angegeben.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobsAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.JobProperties&gt;&gt; GetJobsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.JobProperties&gt;&gt; GetJobsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetJobsAsync" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetJobsAsync () As Task(Of IEnumerable(Of JobProperties))" />
      <MemberSignature Language="F#" Value="abstract member GetJobsAsync : unit -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Devices.JobProperties&gt;&gt;" Usage="registryManager.GetJobsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.JobProperties&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Führt alle Aufträgen für den IoT Hub.
            </summary>
        <returns>IEnumerable von JobProperties aller Aufträge für diese IoT Hub.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetJobsAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.JobProperties&gt;&gt; GetJobsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.JobProperties&gt;&gt; GetJobsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetJobsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetJobsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Devices.JobProperties&gt;&gt;" Usage="registryManager.GetJobsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.JobProperties&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Aufgabenabbruchtoken</param>
        <summary>
            Führt alle Aufträgen für den IoT Hub.
            </summary>
        <returns>IEnumerable von JobProperties aller Aufträge für diese IoT Hub.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRegistryStatisticsAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.RegistryStatistics&gt; GetRegistryStatisticsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.RegistryStatistics&gt; GetRegistryStatisticsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetRegistryStatisticsAsync" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetRegistryStatisticsAsync () As Task(Of RegistryStatistics)" />
      <MemberSignature Language="F#" Value="abstract member GetRegistryStatisticsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.RegistryStatistics&gt;" Usage="registryManager.GetRegistryStatisticsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.RegistryStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft die von den Nutzungsstatistiken für Iot Hub ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRegistryStatisticsAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.RegistryStatistics&gt; GetRegistryStatisticsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.RegistryStatistics&gt; GetRegistryStatisticsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetRegistryStatisticsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetRegistryStatisticsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.RegistryStatistics&gt;" Usage="registryManager.GetRegistryStatisticsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.RegistryStatistics&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">
            Das Token, wodurch die der Vorgang abgebrochen werden.
            </param>
        <summary>
            Ruft die von den Nutzungsstatistiken für Iot Hub ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTwinAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; GetTwinAsync (string deviceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; GetTwinAsync(string deviceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetTwinAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function GetTwinAsync (deviceId As String) As Task(Of Twin)" />
      <MemberSignature Language="F#" Value="abstract member GetTwinAsync : string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="registryManager.GetTwinAsync deviceId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId">Geräte-Id</param>
        <summary>
            Ruft <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> aus IotHub
            </summary>
        <returns>Ziel-Instanz</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTwinAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; GetTwinAsync (string deviceId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; GetTwinAsync(string deviceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.GetTwinAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetTwinAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="registryManager.GetTwinAsync (deviceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">Geräte-Id</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Ruft <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> aus IotHub
            </summary>
        <returns>Ziel-Instanz</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt; ImportDevicesAsync (string importBlobContainerUri, string outputBlobContainerUri);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobProperties&gt; ImportDevicesAsync(string importBlobContainerUri, string outputBlobContainerUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ImportDevicesAsync(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function ImportDevicesAsync (importBlobContainerUri As String, outputBlobContainerUri As String) As Task(Of JobProperties)" />
      <MemberSignature Language="F#" Value="abstract member ImportDevicesAsync : string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;" Usage="registryManager.ImportDevicesAsync (importBlobContainerUri, outputBlobContainerUri)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="importBlobContainerUri" Type="System.String" />
        <Parameter Name="outputBlobContainerUri" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="importBlobContainerUri">Quell-BLOB-Container-URI</param>
        <param name="outputBlobContainerUri">Ziel-BLOB-Container-URI</param>
        <summary>
            Erstellt einen neuen Bulk-Auftrag für den import von geräteregistrierungen in IoT Hub.
            </summary>
        <returns>JobProperties des neu erstellten Auftrags.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt; ImportDevicesAsync (string importBlobContainerUri, string outputBlobContainerUri, string inputBlobName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobProperties&gt; ImportDevicesAsync(string importBlobContainerUri, string outputBlobContainerUri, string inputBlobName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ImportDevicesAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function ImportDevicesAsync (importBlobContainerUri As String, outputBlobContainerUri As String, inputBlobName As String) As Task(Of JobProperties)" />
      <MemberSignature Language="F#" Value="abstract member ImportDevicesAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;" Usage="registryManager.ImportDevicesAsync (importBlobContainerUri, outputBlobContainerUri, inputBlobName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="importBlobContainerUri" Type="System.String" />
        <Parameter Name="outputBlobContainerUri" Type="System.String" />
        <Parameter Name="inputBlobName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="importBlobContainerUri"></param>
        <param name="outputBlobContainerUri"></param>
        <param name="inputBlobName"></param>
        <summary>
            Erstellt einen neuen Bulk-Auftrag für den import von geräteregistrierungen in IoT Hub.
            </summary>
        <returns>JobProperties des neu erstellten Auftrags.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt; ImportDevicesAsync (string importBlobContainerUri, string outputBlobContainerUri, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobProperties&gt; ImportDevicesAsync(string importBlobContainerUri, string outputBlobContainerUri, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ImportDevicesAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ImportDevicesAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;" Usage="registryManager.ImportDevicesAsync (importBlobContainerUri, outputBlobContainerUri, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="importBlobContainerUri" Type="System.String" />
        <Parameter Name="outputBlobContainerUri" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="importBlobContainerUri">Quell-BLOB-Container-URI</param>
        <param name="outputBlobContainerUri">Ziel-BLOB-Container-URI</param>
        <param name="cancellationToken">Aufgabenabbruchtoken</param>
        <summary>
            Erstellt einen neuen Bulk-Auftrag für den import von geräteregistrierungen in IoT Hub.
            </summary>
        <returns>JobProperties des neu erstellten Auftrags.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt; ImportDevicesAsync (string importBlobContainerUri, string outputBlobContainerUri, string inputBlobName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.JobProperties&gt; ImportDevicesAsync(string importBlobContainerUri, string outputBlobContainerUri, string inputBlobName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ImportDevicesAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ImportDevicesAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;" Usage="registryManager.ImportDevicesAsync (importBlobContainerUri, outputBlobContainerUri, inputBlobName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.JobProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="importBlobContainerUri" Type="System.String" />
        <Parameter Name="outputBlobContainerUri" Type="System.String" />
        <Parameter Name="inputBlobName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="importBlobContainerUri"></param>
        <param name="outputBlobContainerUri"></param>
        <param name="inputBlobName"></param>
        <param name="cancellationToken"></param>
        <summary>
            Erstellt einen neuen Bulk-Auftrag für den import von geräteregistrierungen in IoT Hub.
            </summary>
        <returns>JobProperties des neu erstellten Auftrags.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task OpenAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task OpenAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.OpenAsync" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function OpenAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member OpenAsync : unit -&gt; System.Threading.Tasks.Task" Usage="registryManager.OpenAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Öffnen Sie explizit die RegistryManager-Instanz.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task RemoveDeviceAsync (Microsoft.Azure.Devices.Device device);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveDeviceAsync(class Microsoft.Azure.Devices.Device device) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.RemoveDeviceAsync(Microsoft.Azure.Devices.Device)" />
      <MemberSignature Language="F#" Value="abstract member RemoveDeviceAsync : Microsoft.Azure.Devices.Device -&gt; System.Threading.Tasks.Task" Usage="registryManager.RemoveDeviceAsync device" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="device" Type="Microsoft.Azure.Devices.Device" />
      </Parameters>
      <Docs>
        <param name="device">
            Das Gerät gelöscht werden soll.
            </param>
        <summary>
            Löscht einen zuvor registrierten Gerät aus dem System.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task RemoveDeviceAsync (string deviceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveDeviceAsync(string deviceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.RemoveDeviceAsync(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function RemoveDeviceAsync (deviceId As String) As Task" />
      <MemberSignature Language="F#" Value="abstract member RemoveDeviceAsync : string -&gt; System.Threading.Tasks.Task" Usage="registryManager.RemoveDeviceAsync deviceId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            Die Id des Geräts gelöscht werden soll.
            </param>
        <summary>
            Löscht einen zuvor registrierten Gerät aus dem System.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task RemoveDeviceAsync (Microsoft.Azure.Devices.Device device, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveDeviceAsync(class Microsoft.Azure.Devices.Device device, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.RemoveDeviceAsync(Microsoft.Azure.Devices.Device,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveDeviceAsync : Microsoft.Azure.Devices.Device * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="registryManager.RemoveDeviceAsync (device, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="device" Type="Microsoft.Azure.Devices.Device" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="device">
            Das Gerät gelöscht werden soll.
            </param>
        <param name="cancellationToken">
            Das Token, wodurch die der Vorgang abgebrochen werden.
            </param>
        <summary>
            Löscht einen zuvor registrierten Gerät aus dem System.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task RemoveDeviceAsync (string deviceId, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RemoveDeviceAsync(string deviceId, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.RemoveDeviceAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveDeviceAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="registryManager.RemoveDeviceAsync (deviceId, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">
            Die Id des Geräts gelöscht werden soll.
            </param>
        <param name="cancellationToken">
            Das Token, wodurch die der Vorgang abgebrochen werden.
            </param>
        <summary>
            Löscht einen zuvor registrierten Gerät aus dem System.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDevices2Async">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; RemoveDevices2Async (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; RemoveDevices2Async(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.RemoveDevices2Async(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function RemoveDevices2Async (devices As IEnumerable(Of Device)) As Task(Of BulkRegistryOperationResult)" />
      <MemberSignature Language="F#" Value="abstract member RemoveDevices2Async : seq&lt;Microsoft.Azure.Devices.Device&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;" Usage="registryManager.RemoveDevices2Async devices" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
      </Parameters>
      <Docs>
        <param name="devices">
            Die Geräte, die gelöscht werden.
            </param>
        <summary>
            Wird eine Liste der zuvor registrierte Geräte aus dem System gelöscht.
            </summary>
        <returns>Gibt ein BulkRegistryOperationResult-Objekt</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDevices2Async">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; RemoveDevices2Async (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices, bool forceRemove, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; RemoveDevices2Async(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices, bool forceRemove, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.RemoveDevices2Async(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device},System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveDevices2Async : seq&lt;Microsoft.Azure.Devices.Device&gt; * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;" Usage="registryManager.RemoveDevices2Async (devices, forceRemove, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="devices">
            Die Geräte, die gelöscht werden.
            </param>
        <param name="forceRemove">
            Erzwingt, dass das Objekt entfernt werden soll, selbst wenn er aktualisiert wurde, seit es zuletzt abgerufen wurde.
            </param>
        <param name="cancellationToken">
            Das Token, wodurch die der Vorgang abgebrochen werden.
            </param>
        <summary>
            Wird eine Liste der zuvor registrierte Geräte aus dem System gelöscht.
            </summary>
        <returns>Gibt ein BulkRegistryOperationResult-Objekt</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;string[]&gt; RemoveDevicesAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string[]&gt; RemoveDevicesAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.RemoveDevicesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function RemoveDevicesAsync (devices As IEnumerable(Of Device)) As Task(Of String())" />
      <MemberSignature Language="F#" Value="abstract member RemoveDevicesAsync : seq&lt;Microsoft.Azure.Devices.Device&gt; -&gt; System.Threading.Tasks.Task&lt;string[]&gt;" Usage="registryManager.RemoveDevicesAsync devices" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use RemoveDevices2Async")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
      </Parameters>
      <Docs>
        <param name="devices">
            Die Geräte, die gelöscht werden.
            </param>
        <summary>
            Wird eine Liste der zuvor registrierte Geräte aus dem System gelöscht.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;string[]&gt; RemoveDevicesAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices, bool forceRemove, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string[]&gt; RemoveDevicesAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices, bool forceRemove, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.RemoveDevicesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device},System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RemoveDevicesAsync : seq&lt;Microsoft.Azure.Devices.Device&gt; * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string[]&gt;" Usage="registryManager.RemoveDevicesAsync (devices, forceRemove, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use RemoveDevices2Async")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="devices">
            Die Geräte, die gelöscht werden.
            </param>
        <param name="forceRemove">
            Erzwingt, dass das Objekt, ohne nach einer Übereinstimmung ETag entfernt werden soll.
            </param>
        <param name="cancellationToken">
            Das Token, wodurch die der Vorgang abgebrochen werden.
            </param>
        <summary>
            Wird eine Liste der zuvor registrierte Geräte aus dem System gelöscht.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceTwinAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; ReplaceTwinAsync (string deviceId, Microsoft.Azure.Devices.Shared.Twin newTwin, string etag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; ReplaceTwinAsync(string deviceId, class Microsoft.Azure.Devices.Shared.Twin newTwin, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ReplaceTwinAsync(System.String,Microsoft.Azure.Devices.Shared.Twin,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function ReplaceTwinAsync (deviceId As String, newTwin As Twin, etag As String) As Task(Of Twin)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceTwinAsync : string * Microsoft.Azure.Devices.Shared.Twin * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="registryManager.ReplaceTwinAsync (deviceId, newTwin, etag)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="newTwin" Type="Microsoft.Azure.Devices.Shared.Twin" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId">Geräte-ID</param>
        <param name="newTwin">Neues Ziel-Objekt zum Ersetzen durch</param>
        <param name="etag">Ziel des etag</param>
        <summary>
            Aktualisiert die änderbare Felder<see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></summary>
        <returns>Aktualisierte und Instanz</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceTwinAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; ReplaceTwinAsync (string deviceId, string newTwinJson, string etag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; ReplaceTwinAsync(string deviceId, string newTwinJson, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ReplaceTwinAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function ReplaceTwinAsync (deviceId As String, newTwinJson As String, etag As String) As Task(Of Twin)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceTwinAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="registryManager.ReplaceTwinAsync (deviceId, newTwinJson, etag)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="newTwinJson" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId">Geräte-ID</param>
        <param name="newTwinJson">Neue und JSON-Code durch Ersetzen</param>
        <param name="etag">Ziel des etag</param>
        <summary>
            Aktualisiert die änderbare Felder<see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></summary>
        <returns>Aktualisierte und Instanz</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceTwinAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; ReplaceTwinAsync (string deviceId, Microsoft.Azure.Devices.Shared.Twin newTwin, string etag, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; ReplaceTwinAsync(string deviceId, class Microsoft.Azure.Devices.Shared.Twin newTwin, string etag, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ReplaceTwinAsync(System.String,Microsoft.Azure.Devices.Shared.Twin,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceTwinAsync : string * Microsoft.Azure.Devices.Shared.Twin * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="registryManager.ReplaceTwinAsync (deviceId, newTwin, etag, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="newTwin" Type="Microsoft.Azure.Devices.Shared.Twin" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">Geräte-ID</param>
        <param name="newTwin">Neues Ziel-Objekt zum Ersetzen durch</param>
        <param name="etag">Ziel des etag</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Aktualisiert die änderbare Felder<see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></summary>
        <returns>Aktualisierte und Instanz</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReplaceTwinAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; ReplaceTwinAsync (string deviceId, string newTwinJson, string etag, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; ReplaceTwinAsync(string deviceId, string newTwinJson, string etag, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.ReplaceTwinAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReplaceTwinAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="registryManager.ReplaceTwinAsync (deviceId, newTwinJson, etag, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="newTwinJson" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">Geräte-ID</param>
        <param name="newTwinJson">Neue und JSON-Code durch Ersetzen</param>
        <param name="etag">Ziel des etag</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Aktualisiert die änderbare Felder<see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></summary>
        <returns>Aktualisierte und Instanz</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt; UpdateDeviceAsync (Microsoft.Azure.Devices.Device device);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Device&gt; UpdateDeviceAsync(class Microsoft.Azure.Devices.Device device) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateDeviceAsync(Microsoft.Azure.Devices.Device)" />
      <MemberSignature Language="F#" Value="abstract member UpdateDeviceAsync : Microsoft.Azure.Devices.Device -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;" Usage="registryManager.UpdateDeviceAsync device" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="device" Type="Microsoft.Azure.Devices.Device" />
      </Parameters>
      <Docs>
        <param name="device">
            Das Objekt mit aktualisierten Felder.
            </param>
        <summary>
            Aktualisieren Sie die änderbare Felder von der geräteregistrierung
            </summary>
        <returns>Echo wieder am Geräteobjekt mit aktualisierten etags</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt; UpdateDeviceAsync (Microsoft.Azure.Devices.Device device, bool forceUpdate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Device&gt; UpdateDeviceAsync(class Microsoft.Azure.Devices.Device device, bool forceUpdate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateDeviceAsync(Microsoft.Azure.Devices.Device,System.Boolean)" />
      <MemberSignature Language="F#" Value="abstract member UpdateDeviceAsync : Microsoft.Azure.Devices.Device * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;" Usage="registryManager.UpdateDeviceAsync (device, forceUpdate)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="device" Type="Microsoft.Azure.Devices.Device" />
        <Parameter Name="forceUpdate" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="device">
            Das Objekt mit aktualisierten Felder.
            </param>
        <param name="forceUpdate">
            Erzwingt, dass das Objekt ohne Berücksichtigung nach einer Übereinstimmung ETag ersetzt werden.
            </param>
        <summary>
            Aktualisieren Sie die änderbare Felder von der geräteregistrierung
            </summary>
        <returns>Echo wieder am Geräteobjekt mit aktualisierten etags</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt; UpdateDeviceAsync (Microsoft.Azure.Devices.Device device, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Device&gt; UpdateDeviceAsync(class Microsoft.Azure.Devices.Device device, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateDeviceAsync(Microsoft.Azure.Devices.Device,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateDeviceAsync : Microsoft.Azure.Devices.Device * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;" Usage="registryManager.UpdateDeviceAsync (device, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="device" Type="Microsoft.Azure.Devices.Device" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="device">
            Das Objekt mit aktualisierten Felder.
            </param>
        <param name="cancellationToken">
            Das Token, wodurch die der Vorgang abgebrochen werden.
            </param>
        <summary>
            Aktualisieren Sie die änderbare Felder von der geräteregistrierung
            </summary>
        <returns>Echo wieder am Geräteobjekt mit aktualisierten etags</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDeviceAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt; UpdateDeviceAsync (Microsoft.Azure.Devices.Device device, bool forceUpdate, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Device&gt; UpdateDeviceAsync(class Microsoft.Azure.Devices.Device device, bool forceUpdate, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateDeviceAsync(Microsoft.Azure.Devices.Device,System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateDeviceAsync : Microsoft.Azure.Devices.Device * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;" Usage="registryManager.UpdateDeviceAsync (device, forceUpdate, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Device&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="device" Type="Microsoft.Azure.Devices.Device" />
        <Parameter Name="forceUpdate" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="device">
            Das Objekt mit aktualisierten Felder.
            </param>
        <param name="forceUpdate">
            Erzwingt, dass das Objekt ersetzt werden, auch wenn er aktualisiert wurde, seit es zuletzt abgerufen wurde.
            </param>
        <param name="cancellationToken">
            Das Token, wodurch die der Vorgang abgebrochen werden.
            </param>
        <summary>
            Aktualisieren Sie die änderbare Felder von der geräteregistrierung
            </summary>
        <returns>Echo wieder am Geräteobjekt mit aktualisierten etags</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDevices2Async">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateDevices2Async (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateDevices2Async(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateDevices2Async(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function UpdateDevices2Async (devices As IEnumerable(Of Device)) As Task(Of BulkRegistryOperationResult)" />
      <MemberSignature Language="F#" Value="abstract member UpdateDevices2Async : seq&lt;Microsoft.Azure.Devices.Device&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;" Usage="registryManager.UpdateDevices2Async devices" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
      </Parameters>
      <Docs>
        <param name="devices">
            Geräteobjekte aktualisiert werden.
            </param>
        <summary>
            Aktualisieren einer Liste von Geräten mit dem system
            </summary>
        <returns>Gibt ein BulkRegistryOperationResult-Objekt</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDevices2Async">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateDevices2Async (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices, bool forceUpdate, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateDevices2Async(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices, bool forceUpdate, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateDevices2Async(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device},System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateDevices2Async : seq&lt;Microsoft.Azure.Devices.Device&gt; * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;" Usage="registryManager.UpdateDevices2Async (devices, forceUpdate, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
        <Parameter Name="forceUpdate" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="devices">
            Geräteobjekte aktualisiert werden.
            </param>
        <param name="forceUpdate">
            Erzwingt, dass das Objekt ersetzt werden, auch wenn er aktualisiert wurde, seit es zuletzt abgerufen wurde.
            </param>
        <param name="cancellationToken">
            Das Token, wodurch die der Vorgang abgebrochen werden.
            </param>
        <summary>
            Aktualisieren einer Liste von Geräten mit dem system
            </summary>
        <returns>Gibt ein BulkRegistryOperationResult-Objekt</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;string[]&gt; UpdateDevicesAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string[]&gt; UpdateDevicesAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateDevicesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function UpdateDevicesAsync (devices As IEnumerable(Of Device)) As Task(Of String())" />
      <MemberSignature Language="F#" Value="abstract member UpdateDevicesAsync : seq&lt;Microsoft.Azure.Devices.Device&gt; -&gt; System.Threading.Tasks.Task&lt;string[]&gt;" Usage="registryManager.UpdateDevicesAsync devices" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use UpdateDevices2Async")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
      </Parameters>
      <Docs>
        <param name="devices">
            Geräteobjekte aktualisiert werden.
            </param>
        <summary>
            Aktualisieren einer Liste von Geräten mit dem system
            </summary>
        <returns>Gibt ein Zeichenfolgenarray von Fehlermeldungen zurück</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDevicesAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;string[]&gt; UpdateDevicesAsync (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt; devices, bool forceUpdate, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;string[]&gt; UpdateDevicesAsync(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Device&gt; devices, bool forceUpdate, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateDevicesAsync(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Device},System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateDevicesAsync : seq&lt;Microsoft.Azure.Devices.Device&gt; * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string[]&gt;" Usage="registryManager.UpdateDevicesAsync (devices, forceUpdate, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Use UpdateDevices2Async")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String[]&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="devices" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Device&gt;" />
        <Parameter Name="forceUpdate" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="devices">
            Geräteobjekte aktualisiert werden.
            </param>
        <param name="forceUpdate">
            Erzwingt, dass das Objekt ersetzt werden, auch wenn er aktualisiert wurde, seit es zuletzt abgerufen wurde.
            </param>
        <param name="cancellationToken">
            Das Token, wodurch die der Vorgang abgebrochen werden.
            </param>
        <summary>
            Aktualisieren einer Liste von Geräten mit dem system
            </summary>
        <returns>Gibt ein Zeichenfolgenarray von Fehlermeldungen zurück</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTwinAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; UpdateTwinAsync (string deviceId, Microsoft.Azure.Devices.Shared.Twin twinPatch, string etag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; UpdateTwinAsync(string deviceId, class Microsoft.Azure.Devices.Shared.Twin twinPatch, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateTwinAsync(System.String,Microsoft.Azure.Devices.Shared.Twin,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function UpdateTwinAsync (deviceId As String, twinPatch As Twin, etag As String) As Task(Of Twin)" />
      <MemberSignature Language="F#" Value="abstract member UpdateTwinAsync : string * Microsoft.Azure.Devices.Shared.Twin * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="registryManager.UpdateTwinAsync (deviceId, twinPatch, etag)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="twinPatch" Type="Microsoft.Azure.Devices.Shared.Twin" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId">Geräte-ID</param>
        <param name="twinPatch">Und mit aktualisierten Felder</param>
        <param name="etag">Ziel des etag</param>
        <summary>
            Aktualisiert die änderbare Felder<see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></summary>
        <returns>Aktualisierte und Instanz</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTwinAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; UpdateTwinAsync (string deviceId, string jsonTwinPatch, string etag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; UpdateTwinAsync(string deviceId, string jsonTwinPatch, string etag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateTwinAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function UpdateTwinAsync (deviceId As String, jsonTwinPatch As String, etag As String) As Task(Of Twin)" />
      <MemberSignature Language="F#" Value="abstract member UpdateTwinAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="registryManager.UpdateTwinAsync (deviceId, jsonTwinPatch, etag)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jsonTwinPatch" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="deviceId">Geräte-ID</param>
        <param name="jsonTwinPatch">Zwei Json mit aktualisierten Felder</param>
        <param name="etag">Ziel des etag</param>
        <summary>
            Aktualisiert die änderbare Felder<see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></summary>
        <returns>Aktualisierte und Instanz</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTwinAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; UpdateTwinAsync (string deviceId, Microsoft.Azure.Devices.Shared.Twin twinPatch, string etag, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; UpdateTwinAsync(string deviceId, class Microsoft.Azure.Devices.Shared.Twin twinPatch, string etag, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateTwinAsync(System.String,Microsoft.Azure.Devices.Shared.Twin,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateTwinAsync : string * Microsoft.Azure.Devices.Shared.Twin * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="registryManager.UpdateTwinAsync (deviceId, twinPatch, etag, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="twinPatch" Type="Microsoft.Azure.Devices.Shared.Twin" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">Geräte-ID</param>
        <param name="twinPatch">Und mit aktualisierten Felder</param>
        <param name="etag">Ziel des etag</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Aktualisiert die änderbare Felder<see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></summary>
        <returns>Aktualisierte und Instanz</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTwinAsync">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt; UpdateTwinAsync (string deviceId, string jsonTwinPatch, string etag, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; UpdateTwinAsync(string deviceId, string jsonTwinPatch, string etag, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateTwinAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateTwinAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" Usage="registryManager.UpdateTwinAsync (deviceId, jsonTwinPatch, etag, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.Shared.Twin&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deviceId" Type="System.String" />
        <Parameter Name="jsonTwinPatch" Type="System.String" />
        <Parameter Name="etag" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deviceId">Geräte-ID</param>
        <param name="jsonTwinPatch">Zwei Json mit aktualisierten Felder</param>
        <param name="etag">Ziel des etag</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Aktualisiert die änderbare Felder<see cref="T:Microsoft.Azure.Devices.Shared.Twin" /></summary>
        <returns>Aktualisierte und Instanz</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTwins2Async">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateTwins2Async (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Shared.Twin&gt; twins);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateTwins2Async(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; twins) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateTwins2Async(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Shared.Twin})" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function UpdateTwins2Async (twins As IEnumerable(Of Twin)) As Task(Of BulkRegistryOperationResult)" />
      <MemberSignature Language="F#" Value="abstract member UpdateTwins2Async : seq&lt;Microsoft.Azure.Devices.Shared.Twin&gt; -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;" Usage="registryManager.UpdateTwins2Async twins" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="twins" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" />
      </Parameters>
      <Docs>
        <param name="twins">Liste der <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s mit aktualisierten Felder</param>
        <summary>
            Aktualisieren Sie die änderbare Felder für eine Liste der <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s zuvor innerhalb des Systems erstellt haben.
            </summary>
        <returns>Ergebnis des Massenvorgangs update</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTwins2Async">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateTwins2Async (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Shared.Twin&gt; twins, bool forceUpdate);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateTwins2Async(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; twins, bool forceUpdate) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateTwins2Async(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Shared.Twin},System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public MustOverride Function UpdateTwins2Async (twins As IEnumerable(Of Twin), forceUpdate As Boolean) As Task(Of BulkRegistryOperationResult)" />
      <MemberSignature Language="F#" Value="abstract member UpdateTwins2Async : seq&lt;Microsoft.Azure.Devices.Shared.Twin&gt; * bool -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;" Usage="registryManager.UpdateTwins2Async (twins, forceUpdate)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="twins" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" />
        <Parameter Name="forceUpdate" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="twins">Liste der <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s mit aktualisierten Felder</param>
        <param name="forceUpdate">Erzwingt, dass die <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> Objekt aktualisiert werden, auch wenn er geändert hat, seit es zuletzt abgerufen wurde.</param>
        <summary>
            Aktualisieren Sie die änderbare Felder für eine Liste der <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s zuvor innerhalb des Systems erstellt haben.
            </summary>
        <returns>Ergebnis des Massenvorgangs update</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTwins2Async">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateTwins2Async (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Shared.Twin&gt; twins, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateTwins2Async(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; twins, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateTwins2Async(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Shared.Twin},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateTwins2Async : seq&lt;Microsoft.Azure.Devices.Shared.Twin&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;" Usage="registryManager.UpdateTwins2Async (twins, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="twins" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="twins">Liste der <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s mit aktualisierten Felder</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Aktualisieren Sie die änderbare Felder für eine Liste der <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s zuvor innerhalb des Systems erstellt haben.
            </summary>
        <returns>Ergebnis des Massenvorgangs update</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateTwins2Async">
      <MemberSignature Language="C#" Value="public abstract System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateTwins2Async (System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Shared.Twin&gt; twins, bool forceUpdate, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Devices.BulkRegistryOperationResult&gt; UpdateTwins2Async(class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Devices.Shared.Twin&gt; twins, bool forceUpdate, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Devices.RegistryManager.UpdateTwins2Async(System.Collections.Generic.IEnumerable{Microsoft.Azure.Devices.Shared.Twin},System.Boolean,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateTwins2Async : seq&lt;Microsoft.Azure.Devices.Shared.Twin&gt; * bool * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;" Usage="registryManager.UpdateTwins2Async (twins, forceUpdate, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Devices</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Devices.BulkRegistryOperationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="twins" Type="System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Devices.Shared.Twin&gt;" />
        <Parameter Name="forceUpdate" Type="System.Boolean" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="twins">Liste der <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s mit aktualisierten Felder</param>
        <param name="forceUpdate">Erzwingt, dass die <see cref="T:Microsoft.Azure.Devices.Shared.Twin" /> Objekt aktualisiert werden, auch wenn er geändert hat, seit es zuletzt abgerufen wurde.</param>
        <param name="cancellationToken">Abbruchtoken</param>
        <summary>
            Aktualisieren Sie die änderbare Felder für eine Liste der <see cref="T:Microsoft.Azure.Devices.Shared.Twin" />s zuvor innerhalb des Systems erstellt haben.
            </summary>
        <returns>Ergebnis des Massenvorgangs update</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>