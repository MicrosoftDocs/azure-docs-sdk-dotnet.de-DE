<Type Name="FabricClient+ServiceGroupManagementClient" FullName="System.Fabric.FabricClient+ServiceGroupManagementClient">
  <TypeSignature Language="C#" Value="public class FabricClient.ServiceGroupManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi beforefieldinit FabricClient/ServiceGroupManagementClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.ServiceGroupManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public Class FabricClient.ServiceGroupManagementClient" />
  <TypeSignature Language="F#" Value="type FabricClient.ServiceGroupManagementClient = class" />
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
      <para>Ermöglicht es Client Side Erstellung, Löschung und Überprüfung der Dienstgruppen innerhalb des Clusters wie den <see cref="T:System.Fabric.FabricClient.ServiceManagementClient" /> für reguläre Dienste.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateServiceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceGroupAsync (System.Fabric.Description.ServiceGroupDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceGroupAsync(class System.Fabric.Description.ServiceGroupDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupAsync(System.Fabric.Description.ServiceGroupDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateServiceGroupAsync (description As ServiceGroupDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.CreateServiceGroupAsync : System.Fabric.Description.ServiceGroupDescription -&gt; System.Threading.Tasks.Task" Usage="serviceGroupManagementClient.CreateServiceGroupAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ServiceGroupDescription" />
      </Parameters>
      <Docs>
        <param name="description">Die <see cref="T:System.Fabric.Description.ServiceGroupDescription" /> der beschrieben wird, die Gruppe und zu ihren Membern.</param>
        <summary>
            Erstellt asynchron eine Dienstgruppe aus der angegebenen <see cref="T:System.Fabric.Description.ServiceGroupDescription" />.
            </summary>
        <returns>Der Task, der den asynchronen Dienstvorgangs Gruppe erstellen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceGroupAsync (System.Fabric.Description.ServiceGroupDescription description, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceGroupAsync(class System.Fabric.Description.ServiceGroupDescription description, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupAsync(System.Fabric.Description.ServiceGroupDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CreateServiceGroupAsync : System.Fabric.Description.ServiceGroupDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceGroupManagementClient.CreateServiceGroupAsync (description, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ServiceGroupDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="description">Die <see cref="T:System.Fabric.Description.ServiceGroupDescription" /> der beschrieben wird, die Gruppe und zu ihren Membern.</param>
        <param name="timeout">Zeitspanne, die die maximale Zeitdauer, die Service Fabric diesen Vorgang definiert, um den Vorgang fortzusetzen, vor der Rückgabe eine Timeoutausnahme ausgelöst werden kann.</param>
        <param name="cancellationToken">Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang.  Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.  Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</param>
        <summary>
            Erstellt asynchron eine Dienstgruppe aus der angegebenen <see cref="T:System.Fabric.Description.ServiceGroupDescription" /> mit dem angegebenen Timeout und <see cref="T:System.Threading.CancellationToken" />.
            </summary>
        <returns>Der Task, der den asynchronen Dienstvorgangs Gruppe erstellen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceGroupFromTemplateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceGroupFromTemplateAsync (System.Fabric.Description.ServiceGroupFromTemplateDescription serviceGroupFromTemplateDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceGroupFromTemplateAsync(class System.Fabric.Description.ServiceGroupFromTemplateDescription serviceGroupFromTemplateDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupFromTemplateAsync(System.Fabric.Description.ServiceGroupFromTemplateDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateServiceGroupFromTemplateAsync : System.Fabric.Description.ServiceGroupFromTemplateDescription -&gt; System.Threading.Tasks.Task" Usage="serviceGroupManagementClient.CreateServiceGroupFromTemplateAsync serviceGroupFromTemplateDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceGroupFromTemplateDescription" Type="System.Fabric.Description.ServiceGroupFromTemplateDescription" />
      </Parameters>
      <Docs>
        <param name="serviceGroupFromTemplateDescription">
          <para>Beschreibt die Dienstgruppe aus Gruppe Dienstvorlage, die im Anwendungsmanifest angegebene erstellt werden.</para>
        </param>
        <summary>
          <para>Erstellt eine Dienstgruppe mithilfe einer Dienstvorlage in der Gruppe ein, die in das aktuelle Anwendungsmanifest vordefiniert ist.</para>
        </summary>
        <returns>
          <para>Der Task, der den asynchronen Dienstvorgangs Gruppe erstellen.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceGroupFromTemplateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceGroupFromTemplateAsync (System.Fabric.Description.ServiceGroupFromTemplateDescription serviceGroupFromTemplateDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceGroupFromTemplateAsync(class System.Fabric.Description.ServiceGroupFromTemplateDescription serviceGroupFromTemplateDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupFromTemplateAsync(System.Fabric.Description.ServiceGroupFromTemplateDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CreateServiceGroupFromTemplateAsync : System.Fabric.Description.ServiceGroupFromTemplateDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceGroupManagementClient.CreateServiceGroupFromTemplateAsync (serviceGroupFromTemplateDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceGroupFromTemplateDescription" Type="System.Fabric.Description.ServiceGroupFromTemplateDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceGroupFromTemplateDescription">
          <para>Beschreibt die Dienstgruppe aus Gruppe Dienstvorlage, die im Anwendungsmanifest angegebene erstellt werden.</para>
        </param>
        <param name="timeout">
          <para>Maximal zulässige Zeit für den Vorgang abschließt, bevor TimeoutException ausgelöst wird.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.  Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.  Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Erstellt eine Dienstgruppe mithilfe einer Dienstvorlage in der Gruppe ein, die in das aktuelle Anwendungsmanifest vordefiniert ist.</para>
        </summary>
        <returns>
          <para>Der Task, der den asynchronen Dienstvorgangs Gruppe erstellen.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceGroupFromTemplateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceGroupFromTemplateAsync (Uri applicationName, Uri serviceName, string serviceTypeName, byte[] initializationData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceGroupFromTemplateAsync(class System.Uri applicationName, class System.Uri serviceName, string serviceTypeName, unsigned int8[] initializationData) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupFromTemplateAsync(System.Uri,System.Uri,System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateServiceGroupFromTemplateAsync (applicationName As Uri, serviceName As Uri, serviceTypeName As String, initializationData As Byte()) As Task" />
      <MemberSignature Language="F#" Value="member this.CreateServiceGroupFromTemplateAsync : Uri * Uri * string * byte[] -&gt; System.Threading.Tasks.Task" Usage="serviceGroupManagementClient.CreateServiceGroupFromTemplateAsync (applicationName, serviceName, serviceTypeName, initializationData)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="initializationData" Type="System.Byte[]" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Name der Anwendung für die Dienst-Gruppe</para>
        </param>
        <param name="serviceName">
          <para>Der Dienstname für die Dienst-Gruppe</para>
        </param>
        <param name="serviceTypeName">
          <para>Typ der Dienstname für die Dienst-Gruppe</para>
        </param>
        <param name="initializationData">
          <para>Die Initialisierungsdaten für die Übergabe in der Gruppe "Datenzugriffsdienst"-Instanz</para>
        </param>
        <summary>
          <para>Erstellt eine Dienstgruppe mithilfe einer Dienstvorlage in der Gruppe ein, die in das aktuelle Anwendungsmanifest vordefiniert ist.</para>
        </summary>
        <returns>
          <para>Der Task, der den asynchronen Dienstvorgangs Gruppe erstellen.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceGroupFromTemplateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceGroupFromTemplateAsync (Uri applicationName, Uri serviceName, string serviceTypeName, byte[] initializationData, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceGroupFromTemplateAsync(class System.Uri applicationName, class System.Uri serviceName, string serviceTypeName, unsigned int8[] initializationData, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.CreateServiceGroupFromTemplateAsync(System.Uri,System.Uri,System.String,System.Byte[],System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CreateServiceGroupFromTemplateAsync : Uri * Uri * string * byte[] * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceGroupManagementClient.CreateServiceGroupFromTemplateAsync (applicationName, serviceName, serviceTypeName, initializationData, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationName" Type="System.Uri" />
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="serviceTypeName" Type="System.String" />
        <Parameter Name="initializationData" Type="System.Byte[]" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationName">
          <para>Name der Anwendung für die Dienst-Gruppe</para>
        </param>
        <param name="serviceName">
          <para>Der Dienstname für die Dienst-Gruppe</para>
        </param>
        <param name="serviceTypeName">
          <para>Typ der Dienstname für die Dienst-Gruppe</para>
        </param>
        <param name="initializationData">
          <para>Die Initialisierungsdaten für die Übergabe in der Gruppe "Datenzugriffsdienst"-Instanz</para>
        </param>
        <param name="timeout">
          <para>Maximal zulässige Zeit für den Vorgang abschließt, bevor TimeoutException ausgelöst wird.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.  Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.  Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Erstellt eine Dienstgruppe mithilfe einer Dienstvorlage in der Gruppe ein, die in das aktuelle Anwendungsmanifest vordefiniert ist.</para>
        </summary>
        <returns>
          <para>Der Task, der den asynchronen Dienstvorgangs Gruppe erstellen.</para>
        </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteServiceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteServiceGroupAsync (Uri serviceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteServiceGroupAsync(class System.Uri serviceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.DeleteServiceGroupAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteServiceGroupAsync (serviceGroupName As Uri) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteServiceGroupAsync : Uri -&gt; System.Threading.Tasks.Task" Usage="serviceGroupManagementClient.DeleteServiceGroupAsync serviceGroupName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceGroupName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceGroupName">
          <para>Der Name der Dienstgruppe gelöscht werden soll.</para>
        </param>
        <summary>
          <para>Löscht asynchron den angegebenen Dienstgruppe.</para>
        </summary>
        <returns>
          <para>Vorgang zum Löschen der Aufgabe, die den asynchronen Dienstgruppe darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteServiceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteServiceGroupAsync (Uri serviceGroupName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteServiceGroupAsync(class System.Uri serviceGroupName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.DeleteServiceGroupAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteServiceGroupAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceGroupManagementClient.DeleteServiceGroupAsync (serviceGroupName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceGroupName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceGroupName">
          <para>Der Name der Dienstgruppe gelöscht werden soll.</para>
        </param>
        <param name="timeout">
          <para>Zeitspanne, die die maximale Zeitdauer, die Service Fabric diesen Vorgang definiert, um den Vorgang fortzusetzen, vor der Rückgabe eine Timeoutausnahme ausgelöst werden kann.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> -Objekt, das beobachten von der Vorgang.  Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.  Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Löscht asynchron auf den angegebenen Dienstgruppe, mit dem angegebenen Timeout und <see cref="T:System.Threading.CancellationToken" />.</para>
        </summary>
        <returns>
          <para>Vorgang zum Löschen der Aufgabe, die den asynchronen Dienstgruppe darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupDescriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceGroupDescription&gt; GetServiceGroupDescriptionAsync (Uri serviceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Description.ServiceGroupDescription&gt; GetServiceGroupDescriptionAsync(class System.Uri serviceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.GetServiceGroupDescriptionAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceGroupDescriptionAsync (serviceGroupName As Uri) As Task(Of ServiceGroupDescription)" />
      <MemberSignature Language="F#" Value="member this.GetServiceGroupDescriptionAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceGroupDescription&gt;" Usage="serviceGroupManagementClient.GetServiceGroupDescriptionAsync serviceGroupName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceGroupDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceGroupName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceGroupName">
          <para>Der Name des Diensts zu gruppieren, deren <see cref="T:System.Fabric.Description.ServiceGroupDescription" /> abgerufen werden sollen.</para>
        </param>
        <summary>
          <para>Ruft asynchron den <see cref="T:System.Fabric.Description.ServiceGroupDescription" /> für die angegebene Dienstgruppe, falls vorhanden.</para>
        </summary>
        <returns>
          <para>Die Aufgabe, die den asynchronen Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceGroupDescriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceGroupDescription&gt; GetServiceGroupDescriptionAsync (Uri serviceGroupName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Description.ServiceGroupDescription&gt; GetServiceGroupDescriptionAsync(class System.Uri serviceGroupName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.GetServiceGroupDescriptionAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceGroupDescriptionAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceGroupDescription&gt;" Usage="serviceGroupManagementClient.GetServiceGroupDescriptionAsync (serviceGroupName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceGroupDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceGroupName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceGroupName">
          <para>Der Name des Diensts zu gruppieren, deren <see cref="T:System.Fabric.Description.ServiceGroupDescription" /> abgerufen werden sollen.</para>
        </param>
        <param name="timeout">
          <para>Zeitspanne, die die maximale Zeitdauer, die Service Fabric diesen Vorgang definiert, um den Vorgang fortzusetzen, vor der Rückgabe eine Timeoutausnahme ausgelöst werden kann.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird.  Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll.  Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Ruft asynchron den <see cref="T:System.Fabric.Description.ServiceGroupDescription" /> für die angegebene Dienstgruppe, falls es vorhanden, mit dem angegebenen Timeout ist und <see cref="T:System.Threading.CancellationToken" />.</para>
        </summary>
        <returns>
          <para>Die Aufgabe, die den asynchronen Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateServiceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateServiceGroupAsync (Uri name, System.Fabric.Description.ServiceGroupUpdateDescription updateDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateServiceGroupAsync(class System.Uri name, class System.Fabric.Description.ServiceGroupUpdateDescription updateDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.UpdateServiceGroupAsync(System.Uri,System.Fabric.Description.ServiceGroupUpdateDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateServiceGroupAsync (name As Uri, updateDescription As ServiceGroupUpdateDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.UpdateServiceGroupAsync : Uri * System.Fabric.Description.ServiceGroupUpdateDescription -&gt; System.Threading.Tasks.Task" Usage="serviceGroupManagementClient.UpdateServiceGroupAsync (name, updateDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="updateDescription" Type="System.Fabric.Description.ServiceGroupUpdateDescription" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der URI der Dienstgruppe aktualisiert wird.</param>
        <param name="updateDescription">Die <see cref="T:System.Fabric.Description.ServiceGroupUpdateDescription" /> , die die aktualisierte Konfiguration für Dienstgruppe angibt.</param>
        <summary>
            Aktualisiert asynchron eine Dienstgruppe, mit der angegebenen Beschreibung.
            </summary>
        <returns>Vorgang zum Aktualisieren der Aufgabe, die den asynchronen Dienstgruppe darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateServiceGroupAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateServiceGroupAsync (Uri name, System.Fabric.Description.ServiceGroupUpdateDescription updateDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateServiceGroupAsync(class System.Uri name, class System.Fabric.Description.ServiceGroupUpdateDescription updateDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceGroupManagementClient.UpdateServiceGroupAsync(System.Uri,System.Fabric.Description.ServiceGroupUpdateDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpdateServiceGroupAsync : Uri * System.Fabric.Description.ServiceGroupUpdateDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceGroupManagementClient.UpdateServiceGroupAsync (name, updateDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.Uri" />
        <Parameter Name="updateDescription" Type="System.Fabric.Description.ServiceGroupUpdateDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">Der Name der URI des Diensts aktualisiert wird.</param>
        <param name="updateDescription">Die <see cref="T:System.Fabric.Description.ServiceGroupUpdateDescription" /> , die die aktualisierte Konfiguration für den Dienst angibt.</param>
        <param name="timeout">Die maximale Zeitdauer lässt das System Diese API wird vor der Rückgabe <see cref="T:System.TimeoutException" />.</param>
        <param name="cancellationToken">Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</param>
        <summary>
            Aktualisiert asynchron eine Dienstgruppe, mit der angegebenen Beschreibung.
            </summary>
        <returns>Vorgang zum Aktualisieren der Aufgabe, die den asynchronen Dienstgruppe darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>