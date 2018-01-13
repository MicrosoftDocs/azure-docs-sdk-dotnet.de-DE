<Type Name="FabricClient+ServiceManagementClient" FullName="System.Fabric.FabricClient+ServiceManagementClient">
  <TypeSignature Language="C#" Value="public sealed class FabricClient.ServiceManagementClient" />
  <TypeSignature Language="ILAsm" Value=".class nested public auto ansi sealed beforefieldinit FabricClient/ServiceManagementClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:System.Fabric.FabricClient.ServiceManagementClient" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class FabricClient.ServiceManagementClient" />
  <TypeSignature Language="F#" Value="type FabricClient.ServiceManagementClient = class" />
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
      <para>Stellt dar, das Aktivieren der Dienste verwaltet werden.</para>
    </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceAsync (System.Fabric.Description.ServiceDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceAsync(class System.Fabric.Description.ServiceDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.CreateServiceAsync(System.Fabric.Description.ServiceDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateServiceAsync (description As ServiceDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.CreateServiceAsync : System.Fabric.Description.ServiceDescription -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.CreateServiceAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ServiceDescription" />
      </Parameters>
      <Docs>
        <param name="description">
          <para>Die Konfiguration für den Dienst. Ein <see cref="T:System.Fabric.Description.ServiceDescription" /> enthält alle Informationen, die zum Erstellen eines Diensts erforderlich sind.</para>
        </param>
        <summary>
          <para>Instanziiert einen Dienst mit der angegebenen Beschreibung.</para>
        </summary>
        <returns>
          <para>Der Dienst wird instanziiert.</para>
        </returns>
        <remarks>
          <para>Der Standardtimeout beträgt eine Minute für die lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
          <para>Service Fabric-Name wird implizit erstellt werden, wenn sie nicht bereits vorhanden ist.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">Wenn <paramref name="description" /> ist null.</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceAsync (System.Fabric.Description.ServiceDescription serviceDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceAsync(class System.Fabric.Description.ServiceDescription serviceDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.CreateServiceAsync(System.Fabric.Description.ServiceDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CreateServiceAsync : System.Fabric.Description.ServiceDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.CreateServiceAsync (serviceDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceDescription" Type="System.Fabric.Description.ServiceDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceDescription">
          <para>Die Konfiguration für den Dienst. Ein <see cref="T:System.Fabric.Description.ServiceDescription" /> enthält alle Informationen, die zum Erstellen eines Diensts erforderlich sind.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" />, die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Instanziiert einen Dienst mit der angegebenen Beschreibung. Nimmt auch in Timeoutintervall, was die maximal zulässige Zeit das System diesen Vorgang fortzusetzen lässt, vor der Rückgabe <see cref="T:System.TimeoutException" /> und Abbruchtoken, das beobachten von der Vorgang. 
            </para>
        </summary>
        <returns>
          <para>Der Dienst wird instanziiert.</para>
        </returns>
        <remarks>
          <para>Service Fabric-Name wird implizit erstellt werden, wenn sie nicht bereits vorhanden ist.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">Wenn <paramref name="serviceDescription" /> ist null.</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceFromTemplateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceFromTemplateAsync (System.Fabric.Description.ServiceFromTemplateDescription serviceFromTemplateDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceFromTemplateAsync(class System.Fabric.Description.ServiceFromTemplateDescription serviceFromTemplateDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.CreateServiceFromTemplateAsync(System.Fabric.Description.ServiceFromTemplateDescription)" />
      <MemberSignature Language="F#" Value="member this.CreateServiceFromTemplateAsync : System.Fabric.Description.ServiceFromTemplateDescription -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.CreateServiceFromTemplateAsync serviceFromTemplateDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceFromTemplateDescription" Type="System.Fabric.Description.ServiceFromTemplateDescription" />
      </Parameters>
      <Docs>
        <param name="serviceFromTemplateDescription">
          <para>Beschreibt den Dienst aus im Anwendungsmanifest angegebene Dienstvorlage erstellt werden.</para>
        </param>
        <summary>
          <para>Instanziiert einen Dienst aus der Vorlage, die im Anwendungsmanifest angegeben.</para>
        </summary>
        <returns>
          <para>Der Dienst wird instanziiert.</para>
        </returns>
        <remarks>
          <para>Service Fabric-Name wird implizit erstellt werden, wenn sie nicht bereits vorhanden ist.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTemplateNotFound" />: Die Dienstvorlage ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceFromTemplateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceFromTemplateAsync (System.Fabric.Description.ServiceFromTemplateDescription serviceFromTemplateDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceFromTemplateAsync(class System.Fabric.Description.ServiceFromTemplateDescription serviceFromTemplateDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.CreateServiceFromTemplateAsync(System.Fabric.Description.ServiceFromTemplateDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CreateServiceFromTemplateAsync : System.Fabric.Description.ServiceFromTemplateDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.CreateServiceFromTemplateAsync (serviceFromTemplateDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceFromTemplateDescription" Type="System.Fabric.Description.ServiceFromTemplateDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceFromTemplateDescription">
          <para>Beschreibt einen Dienst aus im Anwendungsmanifest angegebene Dienstvorlage erstellt werden.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Instanziiert einen Dienst aus der Vorlage, die im Anwendungsmanifest angegeben.</para>
        </summary>
        <returns>
          <para>Der Dienst wird instanziiert.</para>
        </returns>
        <remarks>
          <para>Service Fabric-Name wird implizit erstellt werden, wenn sie nicht bereits vorhanden ist.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTemplateNotFound" />: Die Dienstvorlage ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceFromTemplateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceFromTemplateAsync (Uri applicationName, Uri serviceName, string serviceTypeName, byte[] initializationData);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceFromTemplateAsync(class System.Uri applicationName, class System.Uri serviceName, string serviceTypeName, unsigned int8[] initializationData) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.CreateServiceFromTemplateAsync(System.Uri,System.Uri,System.String,System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function CreateServiceFromTemplateAsync (applicationName As Uri, serviceName As Uri, serviceTypeName As String, initializationData As Byte()) As Task" />
      <MemberSignature Language="F#" Value="member this.CreateServiceFromTemplateAsync : Uri * Uri * string * byte[] -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.CreateServiceFromTemplateAsync (applicationName, serviceName, serviceTypeName, initializationData)" />
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
          <para>Der Service Fabric-Name der Anwendung unter der der Dienst erstellt werden soll.</para>
        </param>
        <param name="serviceName">
          <para>Der Service Fabric-Name des Diensts.</para>
        </param>
        <param name="serviceTypeName">
          <para>Den Namen des Diensttyps. Dies muss identisch mit der ServiceTypeName im Dienstmanifest angegeben sein.</para>
        </param>
        <param name="initializationData">
          <para>Die Initialisierungsdaten darstellt, die benutzerdefinierten Daten, die durch den Ersteller des Diensts bereitgestellt wird. Service Fabric ist diese Daten nicht analysiert werden. Diese Daten in jeder Instanz oder das Replikat in wäre <see cref="T:System.Fabric.StatefulServiceContext" /> oder <see cref="T:System.Fabric.StatelessServiceContext" />.            
            Es kann nicht geändert werden, nachdem der Dienst erstellt wird. 
            </para>
        </param>
        <summary>
          <para>Instanziiert einen Dienst aus der Vorlage, die im Anwendungsmanifest angegeben.</para>
        </summary>
        <returns>
          <para>Der Dienst wird instanziiert.</para>
        </returns>
        <remarks>
          <para>Service Fabric-Name wird implizit erstellt werden, wenn sie nicht bereits vorhanden ist.</para>
          <para>Der Standardtimeout beträgt eine Minute für die lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTemplateNotFound" />: Die Dienstvorlage ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">Wenn <paramref name="applicationName" /> oder <paramref name="serviceName" /> NULL sind.</exception>
        <exception cref="T:System.ArgumentException">Wenn <paramref name="serviceTypeName" /> ist null oder Leerzeichen.</exception>
      </Docs>
    </Member>
    <Member MemberName="CreateServiceFromTemplateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CreateServiceFromTemplateAsync (Uri applicationName, Uri serviceName, string serviceTypeName, byte[] initializationData, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CreateServiceFromTemplateAsync(class System.Uri applicationName, class System.Uri serviceName, string serviceTypeName, unsigned int8[] initializationData, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.CreateServiceFromTemplateAsync(System.Uri,System.Uri,System.String,System.Byte[],System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.CreateServiceFromTemplateAsync : Uri * Uri * string * byte[] * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.CreateServiceFromTemplateAsync (applicationName, serviceName, serviceTypeName, initializationData, timeout, cancellationToken)" />
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
          <para>Der Service Fabric-Name der Anwendung unter der der Dienst erstellt werden soll.</para>
        </param>
        <param name="serviceName">
          <para>Der Service Fabric-Name des Diensts.</para>
        </param>
        <param name="serviceTypeName">
          <para>Den Namen des Diensttyps. Dies muss identisch mit der ServiceTypeName im Dienstmanifest angegeben sein.</para>
        </param>
        <param name="initializationData">
          <para>Die Initialisierungsdaten darstellt, die benutzerdefinierten Daten, die durch den Ersteller des Diensts bereitgestellt wird. Service Fabric ist diese Daten nicht analysiert werden. Diese Daten in jeder Instanz oder das Replikat in wäre <see cref="T:System.Fabric.StatefulServiceContext" /> oder <see cref="T:System.Fabric.StatelessServiceContext" />.            
            Es kann nicht geändert werden, nachdem der Dienst erstellt wird. 
            </para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Instanziiert einen Dienst aus der Vorlage, die im Anwendungsmanifest angegeben.
            Nimmt auch in Timeoutintervall, was die maximal zulässige Zeit das System diesen Vorgang fortzusetzen lässt, vor der Rückgabe <see cref="T:System.TimeoutException" /> und Abbruchtoken, das beobachten von der Vorgang. 
            </para>
        </summary>
        <returns>
          <para>Der Dienst wird instanziiert.</para>
        </returns>
        <remarks>
          <para>Service Fabric-Name wird implizit erstellt werden, wenn sie nicht bereits vorhanden ist.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ServiceTemplateNotFound" />: Die Dienstvorlage ist nicht vorhanden.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">Wenn <paramref name="applicationName" /> oder <paramref name="serviceName" /> NULL sind.</exception>
        <exception cref="T:System.ArgumentException">Wenn <paramref name="serviceTypeName" /> ist null oder Leerzeichen.</exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteServiceAsync (System.Fabric.Description.DeleteServiceDescription deleteServiceDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteServiceAsync(class System.Fabric.Description.DeleteServiceDescription deleteServiceDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.DeleteServiceAsync(System.Fabric.Description.DeleteServiceDescription)" />
      <MemberSignature Language="F#" Value="member this.DeleteServiceAsync : System.Fabric.Description.DeleteServiceDescription -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.DeleteServiceAsync deleteServiceDescription" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deleteServiceDescription" Type="System.Fabric.Description.DeleteServiceDescription" />
      </Parameters>
      <Docs>
        <param name="deleteServiceDescription">
          <para>Die Beschreibung des Diensts gelöscht werden soll.</para>
        </param>
        <summary>
          <para>Löscht die angegebene Dienstinstanz.</para>
        </summary>
        <returns>
          <para>Die gelöschten Dienstinstanz.</para>
        </returns>
        <remarks>
          <para>Service Fabric-Name wird implizit und rekursiv gelöscht, wenn die Anwendung Service Fabric verwaltet werden.</para>
          <para>Ein Aufruf erzwungene löschen kann, dass eine erzwungene laufende normalen löschen konvertieren.</para>
          <para>Der Standardtimeout beträgt eine Minute für die lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">Wenn <paramref name="deleteServiceDescription" /> ist null.</exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteServiceAsync (Uri serviceName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteServiceAsync(class System.Uri serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.DeleteServiceAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function DeleteServiceAsync (serviceName As Uri) As Task" />
      <MemberSignature Language="F#" Value="member this.DeleteServiceAsync : Uri -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.DeleteServiceAsync serviceName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This API is deprecated, use overload taking DeleteServiceDescription instead.", false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Service Fabric-Name des Diensts.</para>
        </param>
        <summary>
          <para>Löscht die angegebene Dienstinstanz.</para>
        </summary>
        <returns>
          <para>Die gelöschten Dienstinstanz.</para>
        </returns>
        <remarks>
          <para>Service Fabric-Name wird implizit und rekursiv gelöscht, wenn die Anwendung Service Fabric verwaltet werden.</para>
          <para>Der Standardtimeout beträgt eine Minute für die lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">Wenn <paramref name="serviceName" /> ist null.</exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteServiceAsync (System.Fabric.Description.DeleteServiceDescription deleteServiceDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteServiceAsync(class System.Fabric.Description.DeleteServiceDescription deleteServiceDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.DeleteServiceAsync(System.Fabric.Description.DeleteServiceDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteServiceAsync : System.Fabric.Description.DeleteServiceDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.DeleteServiceAsync (deleteServiceDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deleteServiceDescription" Type="System.Fabric.Description.DeleteServiceDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="deleteServiceDescription">
          <para>Die Beschreibung des Diensts gelöscht werden soll.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Löscht die angegebene Dienstinstanz.
            Nimmt auch in Timeoutintervall, was die maximal zulässige Zeit das System diesen Vorgang fortzusetzen lässt, vor der Rückgabe <see cref="T:System.TimeoutException" /> und Abbruchtoken, das beobachten von der Vorgang. 
            </para>
        </summary>
        <returns>
          <para>Die gelöschten Dienstinstanz.</para>
        </returns>
        <remarks>
          <para>Service Fabric-Name wird implizit und rekursiv gelöscht, wenn die Anwendung Service Fabric verwaltet werden.</para>
          <para>Ein Aufruf erzwungene löschen kann, dass eine erzwungene laufende normalen löschen konvertieren.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">Wenn <paramref name="deleteServiceDescription" /> ist null.</exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeleteServiceAsync (Uri serviceName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task DeleteServiceAsync(class System.Uri serviceName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.DeleteServiceAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.DeleteServiceAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.DeleteServiceAsync (serviceName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("This API is deprecated, use overload taking DeleteServiceDescription instead.", false)</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Service Fabric-Name des Diensts.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Löscht die angegebene Dienstinstanz.
            Nimmt auch in Timeoutintervall, was die maximal zulässige Zeit das System diesen Vorgang fortzusetzen lässt, vor der Rückgabe <see cref="T:System.TimeoutException" /> und Abbruchtoken, das beobachten von der Vorgang. 
            </para>
        </summary>
        <returns>
          <para>Die gelöschten Dienstinstanz.</para>
        </returns>
        <remarks>
          <para>Service Fabric-Name wird implizit und rekursiv gelöscht, wenn die Anwendung Service Fabric verwaltet werden.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">Wenn <paramref name="serviceName" /> ist null.</exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceDescriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceDescription&gt; GetServiceDescriptionAsync (Uri serviceName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Description.ServiceDescription&gt; GetServiceDescriptionAsync(class System.Uri serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.GetServiceDescriptionAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceDescriptionAsync (serviceName As Uri) As Task(Of ServiceDescription)" />
      <MemberSignature Language="F#" Value="member this.GetServiceDescriptionAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceDescription&gt;" Usage="serviceManagementClient.GetServiceDescriptionAsync serviceName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Service Fabric-Name des Diensts.</para>
        </param>
        <summary>
          <para>Ruft die Beschreibung des Diensts für die angegebene Dienstinstanz.</para>
        </summary>
        <returns>
          <para>Die Dienstbeschreibung für die angegebene Dienstinstanz.</para>
        </returns>
        <remarks>
          <para>Der Standardtimeout beträgt eine Minute für die lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
          <para>
            <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.GetServiceDescriptionAsync(System.Uri)" />ist die effizienteste Methode, um zu bestimmen, ob ein Name mit einem Dienst assoziiert ist.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">Wenn <paramref name="serviceName" /> ist null.</exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceDescriptionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceDescription&gt; GetServiceDescriptionAsync (Uri serviceName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.Description.ServiceDescription&gt; GetServiceDescriptionAsync(class System.Uri serviceName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.GetServiceDescriptionAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceDescriptionAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceDescription&gt;" Usage="serviceManagementClient.GetServiceDescriptionAsync (serviceName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.Description.ServiceDescription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Service Fabric-Name des Diensts. </para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Ruft die Beschreibung des Diensts für die angegebene Dienstinstanz.
            Nimmt auch in Timeoutintervall, was die maximal zulässige Zeit das System diesen Vorgang fortzusetzen lässt, vor der Rückgabe <see cref="T:System.TimeoutException" /> und Abbruchtoken, das beobachten von der Vorgang. 
            </para>
        </summary>
        <returns>
          <para>Die Dienstbeschreibung für die angegebene Dienstinstanz.</para>
        </returns>
        <remarks>
          <para>
            <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.GetServiceDescriptionAsync(System.Uri)" />ist die effizienteste Methode, um zu bestimmen, ob ein Name mit einem Dienst assoziiert ist.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">Wenn <paramref name="serviceName" /> ist null.</exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceManifestAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetServiceManifestAsync (string applicationTypeName, string applicationTypeVersion, string serviceManifestName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetServiceManifestAsync(string applicationTypeName, string applicationTypeVersion, string serviceManifestName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.GetServiceManifestAsync(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetServiceManifestAsync (applicationTypeName As String, applicationTypeVersion As String, serviceManifestName As String) As Task(Of String)" />
      <MemberSignature Language="F#" Value="member this.GetServiceManifestAsync : string * string * string -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="serviceManagementClient.GetServiceManifestAsync (applicationTypeName, applicationTypeVersion, serviceManifestName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="serviceManifestName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para>Der Name des Anwendungsmanifests bereitgestellt.</para>
        </param>
        <param name="applicationTypeVersion">
          <para>Die Version des Anwendungsmanifests bereitgestellt.</para>
        </param>
        <param name="serviceManifestName">
          <para>Der Name des im Dienstmanifest im Manifest Anwendung verwiesen wird.</para>
        </param>
        <summary>
          <para>Ruft die bereitgestellte manifest dienstdokument in den Typnamen für die angegebene Anwendung und die Version des Anwendungstyps ab.</para>
        </summary>
        <returns>
          <para>Die bereitgestellten Dienstmanifest Dokument.</para>
        </returns>
        <remarks>
          <para>Der Standardtimeout beträgt eine Minute für die lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetServiceManifestAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;string&gt; GetServiceManifestAsync (string applicationTypeName, string applicationTypeVersion, string serviceManifestName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;string&gt; GetServiceManifestAsync(string applicationTypeName, string applicationTypeVersion, string serviceManifestName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.GetServiceManifestAsync(System.String,System.String,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.GetServiceManifestAsync : string * string * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;string&gt;" Usage="serviceManagementClient.GetServiceManifestAsync (applicationTypeName, applicationTypeVersion, serviceManifestName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="applicationTypeName" Type="System.String" />
        <Parameter Name="applicationTypeVersion" Type="System.String" />
        <Parameter Name="serviceManifestName" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="applicationTypeName">
          <para>Der Name des Anwendungsmanifests bereitgestellt.</para>
        </param>
        <param name="applicationTypeVersion">
          <para>Die Version des Anwendungsmanifests bereitgestellt.</para>
        </param>
        <param name="serviceManifestName">
          <para>Der Name des im Dienstmanifest im Manifest Anwendung verwiesen wird.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Ruft die bereitgestellte manifest dienstdokument in den Typnamen für die angegebene Anwendung und die Version des Anwendungstyps ab.
            Nimmt auch in Timeoutintervall, was die maximal zulässige Zeit das System diesen Vorgang fortzusetzen lässt, vor der Rückgabe <see cref="T:System.TimeoutException" /> und Abbruchtoken, das beobachten von der Vorgang. 
            </para>
        </summary>
        <returns>
          <para>Die bereitgestellten Dienstmanifest Dokument</para>
        </returns>
        <remarks>
          <para>Der Standardtimeout beträgt eine Minute für die lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentException">Wenn <paramref name="applicationTypeName" /> oder <paramref name="applicationTypeVersion" /> oder <paramref name="serviceManifestName" /> sind Null/leer.</exception>
      </Docs>
    </Member>
    <Member MemberName="RegisterServiceNotificationFilterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; RegisterServiceNotificationFilterAsync (System.Fabric.Description.ServiceNotificationFilterDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; RegisterServiceNotificationFilterAsync(class System.Fabric.Description.ServiceNotificationFilterDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterServiceNotificationFilterAsync (description As ServiceNotificationFilterDescription) As Task(Of Long)" />
      <MemberSignature Language="F#" Value="member this.RegisterServiceNotificationFilterAsync : System.Fabric.Description.ServiceNotificationFilterDescription -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="serviceManagementClient.RegisterServiceNotificationFilterAsync description" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ServiceNotificationFilterDescription" />
      </Parameters>
      <Docs>
        <param name="description">
          <para>Die Beschreibung, der bestimmt, welcher Dienstendpunkt die Auswahländerungsereignisse sollte übermittelt werden, dieser Client über die <see cref="E:System.Fabric.FabricClient.ServiceManagementClient.ServiceNotificationFilterMatched" /> Ereignis.</para>
        </param>
        <summary>
          <para>Registriert eine <see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , das den asynchronen Vorgang darstellt. Das Ergebnis der Aufgabe ist eine ID für den registrierten <see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" /> , die verwendet werden kann, den gleichen Filter durch Aufheben der Registrierung <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UnregisterServiceNotificationFilterAsync(System.Int64)" />.</para>
        </returns>
        <remarks>
          <para>Der Standardtimeout beträgt eine Minute für die lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </remarks>
        <exception cref="T:System.ArgumentNullException">Wenn <paramref name="description" /> ist null.</exception>
      </Docs>
    </Member>
    <Member MemberName="RegisterServiceNotificationFilterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;long&gt; RegisterServiceNotificationFilterAsync (System.Fabric.Description.ServiceNotificationFilterDescription description, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;int64&gt; RegisterServiceNotificationFilterAsync(class System.Fabric.Description.ServiceNotificationFilterDescription description, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RegisterServiceNotificationFilterAsync : System.Fabric.Description.ServiceNotificationFilterDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;int64&gt;" Usage="serviceManagementClient.RegisterServiceNotificationFilterAsync (description, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Int64&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="description" Type="System.Fabric.Description.ServiceNotificationFilterDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="description">
          <para>Die Beschreibung, der bestimmt, welcher Dienstendpunkt die Auswahländerungsereignisse sollte übermittelt werden, dieser Client über die <see cref="E:System.Fabric.FabricClient.ServiceManagementClient.ServiceNotificationFilterMatched" /> Ereignis.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeit zum Verarbeiten der Anforderung vor zulässig <see cref="T:System.TimeoutException" /> ausgelöst wird.</para>
        </param>
        <param name="cancellationToken">
          <para>Für zukünftige Verwendung reserviert.</para>
        </param>
        <summary>
          <para>Registriert eine <see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />.
            Nimmt auch in Timeoutintervall, was die maximal zulässige Zeit das System diesen Vorgang fortzusetzen lässt, vor der Rückgabe <see cref="T:System.TimeoutException" /> und Abbruchtoken, das beobachten von der Vorgang. 
            </para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , das den asynchronen Vorgang darstellt. Das Ergebnis der Aufgabe ist eine ID für den registrierten <see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" /> , die verwendet werden kann, den gleichen Filter durch Aufheben der Registrierung <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.UnregisterServiceNotificationFilterAsync(System.Int64)" />.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.ArgumentNullException">Wenn <paramref name="description" /> ist null.</exception>
      </Docs>
    </Member>
    <Member MemberName="RegisterServicePartitionResolutionChangeHandler">
      <MemberSignature Language="C#" Value="public long RegisterServicePartitionResolutionChangeHandler (Uri serviceName, System.Fabric.ServicePartitionResolutionChangeHandler callback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance int64 RegisterServicePartitionResolutionChangeHandler(class System.Uri serviceName, class System.Fabric.ServicePartitionResolutionChangeHandler callback) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServicePartitionResolutionChangeHandler(System.Uri,System.Fabric.ServicePartitionResolutionChangeHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterServicePartitionResolutionChangeHandler (serviceName As Uri, callback As ServicePartitionResolutionChangeHandler) As Long" />
      <MemberSignature Language="F#" Value="member this.RegisterServicePartitionResolutionChangeHandler : Uri * System.Fabric.ServicePartitionResolutionChangeHandler -&gt; int64" Usage="serviceManagementClient.RegisterServicePartitionResolutionChangeHandler (serviceName, callback)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="callback" Type="System.Fabric.ServicePartitionResolutionChangeHandler" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Service Fabric-Name des Diensts.</para>
        </param>
        <param name="callback">
          <para>Die Funktion, die aufgerufen wird, wenn eine Benachrichtigung eingeht.</para>
        </param>
        <summary>
          <para>Diese API ist veraltet, verwenden Sie <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" /> stattdessen.</para>
        </summary>
        <returns>
          <para>Der Handler, die ausgelöst werden, wenn die Informationen zur Barrierefreiheit von einer Dienstpartition ändert.</para>
        </returns>
        <remarks>
          <para>Benachrichtigung wird Änderungen an Endpunkten oder die Ausnahmen, die aufgetreten sind, während der Aktualisierung der Informationen der Partition enthalten. Diese Überladung wird für partitionierte Singleton-Dienstinstanzen verwendet. Zurückgegebene Int64-Typ ist der rückrufbezeichner der Handle für die Registrierung.</para>
          <para>Benachrichtigungen ist ein Mechanismus, der Benachrichtigungen zu jeder Zeit vorhanden ist, eine Änderung des Dienst-Adresse oder ein Adresse-Auflösung Fehler hinsichtlich einer Dienstpartition den Code des Benutzers Code bietet Interesse ausgelöst hat. Auf diese Weise statt auflösen jedes Mal den aktuellen <see cref="T:System.Fabric.ResolvedServicePartition" /> wird veraltet Programm registriert für Updates.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">Wenn <paramref name="serviceName" /> oder <paramref name="callback" /> null sind.</exception>
      </Docs>
    </Member>
    <Member MemberName="RegisterServicePartitionResolutionChangeHandler">
      <MemberSignature Language="C#" Value="public long RegisterServicePartitionResolutionChangeHandler (Uri serviceName, long partitionKey, System.Fabric.ServicePartitionResolutionChangeHandler callback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance int64 RegisterServicePartitionResolutionChangeHandler(class System.Uri serviceName, int64 partitionKey, class System.Fabric.ServicePartitionResolutionChangeHandler callback) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServicePartitionResolutionChangeHandler(System.Uri,System.Int64,System.Fabric.ServicePartitionResolutionChangeHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterServicePartitionResolutionChangeHandler (serviceName As Uri, partitionKey As Long, callback As ServicePartitionResolutionChangeHandler) As Long" />
      <MemberSignature Language="F#" Value="member this.RegisterServicePartitionResolutionChangeHandler : Uri * int64 * System.Fabric.ServicePartitionResolutionChangeHandler -&gt; int64" Usage="serviceManagementClient.RegisterServicePartitionResolutionChangeHandler (serviceName, partitionKey, callback)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.Int64" />
        <Parameter Name="callback" Type="System.Fabric.ServicePartitionResolutionChangeHandler" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Service Fabric-Name des Diensts.</para>
        </param>
        <param name="partitionKey">
          <para>Der Partitionsschlüssel für die Dienstpartition.</para>
        </param>
        <param name="callback">
          <para>Die Funktion, die aufgerufen wird, wenn eine Benachrichtigung eingeht.</para>
        </param>
        <summary>
          <para>Diese API ist veraltet, verwenden Sie <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" /> stattdessen.</para>
        </summary>
        <returns>
          <para>Der Handler, die ausgelöst werden, wenn die Informationen zur Barrierefreiheit von einer Dienstpartition ändert.</para>
        </returns>
        <remarks>
          <para>Benachrichtigung wird Änderungen an Endpunkten oder die Ausnahmen, die aufgetreten sind, während der Aktualisierung der Informationen der Partition enthalten. Diese Überladung wird für UniformInt64Range partitioniert Dienstinstanzen verwendet. Zurückgegebene Int64-Typ ist der rückrufbezeichner der Handle für die Registrierung.</para>
          <para>Benachrichtigungen ist ein Mechanismus, der Benachrichtigungen zu jeder Zeit vorhanden ist, eine Änderung des Dienst-Adresse oder ein Adresse-Auflösung Fehler hinsichtlich einer Dienstpartition den Code des Benutzers Code bietet Interesse ausgelöst hat. Auf diese Weise statt auflösen jedes Mal den aktuellen <see cref="T:System.Fabric.ResolvedServicePartition" /> wird veraltet Programm registriert für Updates.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">Wenn <paramref name="serviceName" /> oder <paramref name="callback" /> null sind.</exception>
      </Docs>
    </Member>
    <Member MemberName="RegisterServicePartitionResolutionChangeHandler">
      <MemberSignature Language="C#" Value="public long RegisterServicePartitionResolutionChangeHandler (Uri serviceName, string partitionKey, System.Fabric.ServicePartitionResolutionChangeHandler callback);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance int64 RegisterServicePartitionResolutionChangeHandler(class System.Uri serviceName, string partitionKey, class System.Fabric.ServicePartitionResolutionChangeHandler callback) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServicePartitionResolutionChangeHandler(System.Uri,System.String,System.Fabric.ServicePartitionResolutionChangeHandler)" />
      <MemberSignature Language="VB.NET" Value="Public Function RegisterServicePartitionResolutionChangeHandler (serviceName As Uri, partitionKey As String, callback As ServicePartitionResolutionChangeHandler) As Long" />
      <MemberSignature Language="F#" Value="member this.RegisterServicePartitionResolutionChangeHandler : Uri * string * System.Fabric.ServicePartitionResolutionChangeHandler -&gt; int64" Usage="serviceManagementClient.RegisterServicePartitionResolutionChangeHandler (serviceName, partitionKey, callback)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="callback" Type="System.Fabric.ServicePartitionResolutionChangeHandler" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Service Fabric-Name des Diensts.</para>
        </param>
        <param name="partitionKey">
          <para>Der Partitionsschlüssel für die Dienstpartition.</para>
        </param>
        <param name="callback">
          <para>Die Funktion, die aufgerufen wird, wenn eine Benachrichtigung eingeht.</para>
        </param>
        <summary>
          <para>Diese API ist veraltet, verwenden Sie <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" /> stattdessen.</para>
        </summary>
        <returns>
          <para>Der Handler, die ausgelöst werden, wenn die Informationen zur Barrierefreiheit von einer Dienstpartition ändert.</para>
        </returns>
        <remarks>
          <para>Benachrichtigung wird Änderungen an Endpunkten oder die Ausnahmen, die aufgetreten sind, während der Aktualisierung der Informationen der Partition enthalten. Diese Überladung wird für benannte partitioniert Dienstinstanzen verwendet. Zurückgegebene Int64-Typ ist der rückrufbezeichner der Handle für die Registrierung.</para>
          <para>Benachrichtigungen ist ein Mechanismus, der Benachrichtigungen zu jeder Zeit vorhanden ist, eine Änderung des Dienst-Adresse oder ein Adresse-Auflösung Fehler hinsichtlich einer Dienstpartition den Code des Benutzers Code bietet Interesse ausgelöst hat. Auf diese Weise statt auflösen jedes Mal den aktuellen <see cref="T:System.Fabric.ResolvedServicePartition" /> wird veraltet Programm registriert für Updates.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">Wenn <paramref name="serviceName" /> oder <paramref name="callback" /> null sind.</exception>
        <exception cref="T:System.ArgumentException">Wenn <paramref name="partitionKey" /> ist null oder leer.</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveReplicaAsync (string nodeName, Guid partitionId, long replicaOrInstanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaOrInstanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RemoveReplicaAsync(System.String,System.Guid,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveReplicaAsync (nodeName As String, partitionId As Guid, replicaOrInstanceId As Long) As Task" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : string * Guid * int64 -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.RemoveReplicaAsync (nodeName, partitionId, replicaOrInstanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaOrInstanceId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des Knotens.</para>
        </param>
        <param name="partitionId">
          <para>Die Partitions-ID.</para>
        </param>
        <param name="replicaOrInstanceId">
          <para>Der Instanzbezeichner.</para>
        </param>
        <summary>
          <para>Entfernt ein Dienstreplikat, das auf einem Knoten ausgeführt wird.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die die Bestätigung der Anforderung darstellt.</para>
        </returns>
        <remarks>
          <para>Diese API ein Replikat ausgeführt haben die Möglichkeit zum Bereinigen Datenbankzustands ordnungsgemäß heruntergefahren werden. </para>
          <para>Der Standardtimeout beträgt eine Minute für die lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
          <para>Warnung: Es werden keine sicherheitsüberprüfungen ausgeführt, wenn diese API verwendet wird. Falsche Verwendung dieser API kann zu Datenverlusten für zustandsbehaftete Dienste führen.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ReplicaDoesNotExist" />wird zurückgegeben, wenn das Replikat oder eine Instanz-Id auf dem Knoten nicht ausgeführt wird.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaStateForReplicaOperation" />wird zurückgegeben, wenn das Replikat oder eine Instanz-Id kann nicht neu gestartet oder zu diesem Zeitpunkt entfernt werden, da sie einen ungültigen Status aufweist. Beispielsweise wird das Replikat bereits gerade geschlossen wird.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.ArgumentException">Wenn <paramref name="nodeName" /> ist null oder leer.</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveReplicaAsync (string nodeName, Guid partitionId, long replicaOrInstanceId, bool forceRemove);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaOrInstanceId, bool forceRemove) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RemoveReplicaAsync(System.String,System.Guid,System.Int64,System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Public Function RemoveReplicaAsync (nodeName As String, partitionId As Guid, replicaOrInstanceId As Long, forceRemove As Boolean) As Task" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : string * Guid * int64 * bool -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.RemoveReplicaAsync (nodeName, partitionId, replicaOrInstanceId, forceRemove)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaOrInstanceId" Type="System.Int64" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des Knotens.</para>
        </param>
        <param name="partitionId">
          <para>Die Partitions-ID.</para>
        </param>
        <param name="replicaOrInstanceId">
          <para>Der Instanzbezeichner.</para>
        </param>
        <param name="forceRemove">
          <para>Gibt an, ob das Replikat soll eine Möglichkeit gewährt werden, die ordnungsgemäß bereinigen Sie seinen Status und schließen</para>
        </param>
        <summary>
          <para>Entfernt ein Dienstreplikat, das auf einem Knoten ausgeführt wird.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die die Bestätigung der Anforderung darstellt.</para>
        </returns>
        <remarks>
          <para>Diese API ein Replikat ausgeführt haben die Möglichkeit zum Bereinigen Datenbankzustands ordnungsgemäß heruntergefahren werden. </para>
          <para>Wenn die ForceRemove-Flag festgelegt ist, wird keine Gelegenheit angegeben. Service Fabric wird den Host für dieses Replikat beendet, und alle persistenten Status des Replikats verloren. </para>
          <para>Warnung: Es werden keine sicherheitsüberprüfungen ausgeführt, wenn diese API verwendet wird. Falsche Verwendung dieser API kann zu Datenverlusten für zustandsbehaftete Dienste führen.</para>
          <para>Darüber hinaus wirkt sich auf die das Flag ForceRemove alle Replikate, die im selben Prozess gehostet.</para>
          <para>Der Standardtimeout beträgt eine Minute für die lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ReplicaDoesNotExist" />wird zurückgegeben, wenn das Replikat oder eine Instanz-Id auf dem Knoten nicht ausgeführt wird.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaStateForReplicaOperation" />wird zurückgegeben, wenn das Replikat oder eine Instanz-Id kann nicht neu gestartet oder zu diesem Zeitpunkt entfernt werden, da sie einen ungültigen Status aufweist. Beispielsweise wird das Replikat bereits gerade geschlossen wird.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.ArgumentException">Wenn <paramref name="nodeName" /> ist null oder leer.</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveReplicaAsync (string nodeName, Guid partitionId, long replicaOrInstanceId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaOrInstanceId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RemoveReplicaAsync(System.String,System.Guid,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : string * Guid * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.RemoveReplicaAsync (nodeName, partitionId, replicaOrInstanceId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaOrInstanceId" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des Knotens.</para>
        </param>
        <param name="partitionId">
          <para>Die Partitions-ID.</para>
        </param>
        <param name="replicaOrInstanceId">
          <para>Der Instanzbezeichner.</para>
        </param>
        <param name="timeout">
          <para>Die Zeitspanne, die die maximale Zeitdauer definiert können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Entfernt ein Dienstreplikat, das auf einem Knoten ausgeführt wird.
            Nimmt auch in Timeoutintervall, was die maximal zulässige Zeit das System diesen Vorgang fortzusetzen lässt, vor der Rückgabe <see cref="T:System.TimeoutException" /> und Abbruchtoken, das beobachten von der Vorgang. 
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die die Bestätigung der Anforderung darstellt.</para>
        </returns>
        <remarks>
          <para>Diese API ein Replikat ausgeführt haben die Möglichkeit zum Bereinigen Datenbankzustands ordnungsgemäß heruntergefahren werden. </para>
          <para>Warnung: Es werden keine sicherheitsüberprüfungen ausgeführt, wenn diese API verwendet wird. Falsche Verwendung dieser API kann zu Datenverlusten für zustandsbehaftete Dienste führen.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ReplicaDoesNotExist" />wird zurückgegeben, wenn das Replikat oder eine Instanz-Id auf dem Knoten nicht ausgeführt wird.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaStateForReplicaOperation" />wird zurückgegeben, wenn das Replikat oder eine Instanz-Id kann nicht neu gestartet oder zu diesem Zeitpunkt entfernt werden, da sie einen ungültigen Status aufweist. Beispielsweise wird das Replikat bereits gerade geschlossen wird.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.ArgumentException">Wenn <paramref name="nodeName" /> ist null oder leer.</exception>
      </Docs>
    </Member>
    <Member MemberName="RemoveReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RemoveReplicaAsync (string nodeName, Guid partitionId, long replicaOrInstanceId, bool forceRemove, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RemoveReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaOrInstanceId, bool forceRemove, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RemoveReplicaAsync(System.String,System.Guid,System.Int64,System.Boolean,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RemoveReplicaAsync : string * Guid * int64 * bool * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.RemoveReplicaAsync (nodeName, partitionId, replicaOrInstanceId, forceRemove, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaOrInstanceId" Type="System.Int64" />
        <Parameter Name="forceRemove" Type="System.Boolean" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des Knotens.</para>
        </param>
        <param name="partitionId">
          <para>Die Partitions-ID.</para>
        </param>
        <param name="replicaOrInstanceId">
          <para>Der Instanzbezeichner.</para>
        </param>
        <param name="forceRemove">
          <para>Gibt an, ob das Replikat soll eine Möglichkeit gewährt werden, die ordnungsgemäß bereinigen Sie seinen Status und schließen</para>
        </param>
        <param name="timeout">
          <para>Die Zeitspanne, die die maximale Zeitdauer definiert können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Entfernt ein Dienstreplikat, das auf einem Knoten ausgeführt wird.
            Nimmt auch in Timeoutintervall, was die maximal zulässige Zeit das System diesen Vorgang fortzusetzen lässt, vor der Rückgabe <see cref="T:System.TimeoutException" /> und Abbruchtoken, das beobachten von der Vorgang. 
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die die Bestätigung der Anforderung darstellt.</para>
        </returns>
        <remarks>
          <para>Diese API ein Replikat ausgeführt haben die Möglichkeit zum Bereinigen Datenbankzustands ordnungsgemäß heruntergefahren werden. </para>
          <para>Wenn die ForceRemove-Flag festgelegt ist, wird keine Gelegenheit angegeben. Service Fabric wird den Host für dieses Replikat beendet, und alle persistenten Status des Replikats verloren. </para>
          <para>Warnung: Es werden keine sicherheitsüberprüfungen ausgeführt, wenn diese API verwendet wird. Falsche Verwendung dieser API kann zu Datenverlusten für zustandsbehaftete Dienste führen.</para>
          <para>Darüber hinaus wirkt sich auf die das Flag ForceRemove alle Replikate, die im selben Prozess gehostet.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ReplicaDoesNotExist" />wird zurückgegeben, wenn das Replikat oder eine Instanz-Id auf dem Knoten nicht ausgeführt wird.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaStateForReplicaOperation" />wird zurückgegeben, wenn das Replikat oder eine Instanz-Id kann nicht neu gestartet oder zu diesem Zeitpunkt entfernt werden, da sie einen ungültigen Status aufweist. Beispielsweise wird das Replikat bereits gerade geschlossen wird.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.ArgumentException">Wenn <paramref name="nodeName" /> ist null oder leer.</exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync serviceName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Service Fabric-Name der Dienstinstanz.</para>
        </param>
        <summary>
          <para>Fragt das System für die Sammlung von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </summary>
        <returns>
          <para>Der Satz von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </returns>
        <remarks>
          <para>Dies ist eine Beschwerde-basierten Lösung API.</para>
          <para>Die <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri)" /> zurück eine <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Partition angegebenen Dienst. Wenn diese Überladung verwendet wird, das System gibt stets den am nächsten gelegenen <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Dienstpartition.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, System.Fabric.ResolvedServicePartition previousResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, class System.Fabric.ResolvedServicePartition previousResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.Fabric.ResolvedServicePartition)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, previousResult As ResolvedServicePartition) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * System.Fabric.ResolvedServicePartition -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, previousResult)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="previousResult" Type="System.Fabric.ResolvedServicePartition" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Service Fabric-Name der Dienstinstanz.</para>
        </param>
        <param name="previousResult">
          <para>Die vorherige <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Dienstpartition, die der Benutzer annimmt, veraltet ist.</para>
        </param>
        <summary>
          <para>Fragt das System für die Sammlung von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </summary>
        <returns>
          <para>Der Satz von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </returns>
        <remarks>
          <para>Eine Beschwerde basierend Auflösung API.</para>
          <para>Diese Methode zurückgegeben wird ein <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Partition angegebenen Dienst. Wenn diese Überladung verwendet wird, wird das System einen aktuelleren zurückgeben <see cref="T:System.Fabric.ResolvedServicePartition" /> als das Argument "PreviousResult", sofern dieser verfügbar ist. </para>
          <para>PreviousResult Argument ermöglicht dem Benutzer sagen: "This der vorherigen Liste der Endpunkte für diese Partition Service is. Ich habe die Endpunkte, und ich davon ausgehen, dass sie veraltet sind. Zurückgeben Sie mir eine aktuellere Version dieser Menge". Das System in diesem Fall versucht, einen aktuelleren zurückzusetzen <see cref="T:System.Fabric.ResolvedServicePartition" /> in die möglichst effiziente Weise ausgeführt. Wenn keine neuere Version nicht gefunden werden kann, eine <see cref="T:System.Fabric.ResolvedServicePartition" /> mit der gleichen Version zurückgegeben. ResolveServicePartition kann ohne PreviousResult Argument auf null festgelegt ist oder PreviousResult Argument aufgerufen werden. Wie keine Voraussetzung angegeben wird, wird das System die nächstgelegene Kopie zurückgeben der <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Dienstpartition.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, long partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, int64 partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, partitionKey As Long) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * int64 -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Service Fabric-Name der Dienstinstanz.</para>
        </param>
        <param name="partitionKey">
          <para>Der Partitionsschlüssel für die Dienstpartition.</para>
        </param>
        <summary>
          <para>Fragt das System für die Sammlung von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </summary>
        <returns>
          <para>Der Satz von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </returns>
        <remarks>
          <para>Dies ist eine Beschwerde-basierten Lösung API.</para>
          <para>Diese Methode zurückgegeben wird ein <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Partition angegebenen Dienst. Wenn diese Überladung verwendet wird, das System gibt stets den am nächsten gelegenen <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Dienstpartition. </para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, string partitionKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, string partitionKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, partitionKey As String) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Service Fabric-Name der Dienstinstanz.</para>
        </param>
        <param name="partitionKey">
          <para>Der Partitionsschlüssel für die Dienstpartition.</para>
        </param>
        <summary>
          <para>Fragt das System für die Sammlung von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </summary>
        <returns>
          <para>Der Satz von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </returns>
        <remarks>
          <para>Dies ist eine Beschwerde-basierten Lösung API.</para>
          <para>Dadurch wird zurückgegeben, eine <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Partition angegebenen Dienst. Wenn diese Überladung verwendet wird, das System gibt stets den am nächsten gelegenen <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Dienstpartition.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, timeout As TimeSpan) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Service Fabric-Name der Dienstinstanz.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <summary>
          <para>Fragt das System für die Sammlung von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </summary>
        <returns>
          <para>Der Satz von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </returns>
        <remarks>
          <para>Dies ist eine Beschwerde-basierten Lösung API.</para>
          <para>Dadurch wird zurückgegeben, eine <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Partition angegebenen Dienst. Wenn diese Überladung verwendet wird, das System gibt stets den am nächsten gelegenen <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Dienstpartition.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, System.Fabric.ResolvedServicePartition previousResult, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, class System.Fabric.ResolvedServicePartition previousResult, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.Fabric.ResolvedServicePartition,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, previousResult As ResolvedServicePartition, timeout As TimeSpan) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * System.Fabric.ResolvedServicePartition * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, previousResult, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="previousResult" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Service Fabric-Name der Dienstinstanz.</para>
        </param>
        <param name="previousResult">
          <para>Die vorherige <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Dienstpartition, die der Benutzer annimmt, veraltet ist.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <summary>
          <para>Fragt das System für die Sammlung von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </summary>
        <returns>
          <para>Der Satz von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </returns>
        <remarks>
          <para>Dies ist eine Beschwerde-basierten Lösung API.</para>
          <para>Diese Methode zurückgegeben wird ein <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Partition angegebenen Dienst. Wenn diese Überladung verwendet wird, wird das System einen aktuelleren zurückgeben <see cref="T:System.Fabric.ResolvedServicePartition" /> als das Argument "PreviousResult", sofern dieser verfügbar ist.</para>
          <para>PreviousResult Argument ermöglicht dem Benutzer sagen: "This der vorherigen Liste der Endpunkte für diese Partition Service is. Ich habe die Endpunkte, und ich davon ausgehen, dass sie veraltet sind. Zurückgeben Sie mir eine aktuellere Version dieser Menge". Das System in diesem Fall versucht, einen aktuelleren zurückzusetzen <see cref="T:System.Fabric.ResolvedServicePartition" /> in die möglichst effiziente Weise ausgeführt. Wenn keine neuere Version nicht gefunden werden kann, eine <see cref="T:System.Fabric.ResolvedServicePartition" /> mit der gleichen Version zurückgegeben. ResolveServicePartition kann ohne PreviousResult Argument auf null festgelegt ist oder PreviousResult Argument aufgerufen werden. Wie keine Voraussetzung angegeben wird, wird das System die nächstgelegene Kopie zurückgeben der <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Dienstpartition.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, long partitionKey, System.Fabric.ResolvedServicePartition previousResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, int64 partitionKey, class System.Fabric.ResolvedServicePartition previousResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.Int64,System.Fabric.ResolvedServicePartition)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, partitionKey As Long, previousResult As ResolvedServicePartition) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * int64 * System.Fabric.ResolvedServicePartition -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey, previousResult)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.Int64" />
        <Parameter Name="previousResult" Type="System.Fabric.ResolvedServicePartition" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Service Fabric-Name der Dienstinstanz.</para>
        </param>
        <param name="partitionKey">
          <para>Der Partitionsschlüssel für die Dienstpartition.</para>
        </param>
        <param name="previousResult">
          <para>Die vorherige <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Dienstpartition, die der Benutzer annimmt, veraltet ist.</para>
        </param>
        <summary>
          <para>Fragt das System für die Sammlung von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </summary>
        <returns>
          <para>Der Satz von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </returns>
        <remarks>
          <para>Dies ist eine Beschwerde-basierten Lösung API.</para>
          <para>Dadurch wird zurückgegeben, eine <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Partition angegebenen Dienst. Wenn diese Überladung verwendet wird, wird das System einen aktuelleren zurückgeben <see cref="T:System.Fabric.ResolvedServicePartition" /> als das Argument "PreviousResult", sofern dieser verfügbar ist. </para>
          <para>PreviousResult Argument ermöglicht dem Benutzer sagen: "This der vorherigen Liste der Endpunkte für diese Partition Service is. Ich habe die Endpunkte, und ich davon ausgehen, dass sie veraltet sind. Zurückgeben Sie mir eine aktuellere Version dieser Menge". Das System in diesem Fall versucht, einen aktuelleren zurückzusetzen <see cref="T:System.Fabric.ResolvedServicePartition" /> in die möglichst effiziente Weise ausgeführt. Wenn keine neuere Version nicht gefunden werden kann, eine <see cref="T:System.Fabric.ResolvedServicePartition" /> mit der gleichen Version zurückgegeben. ResolveServicePartition kann ohne PreviousResult Argument auf null festgelegt ist oder PreviousResult Argument aufgerufen werden. Wie keine Voraussetzung angegeben wird, wird das System die nächstgelegene Kopie zurückgeben der <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Dienstpartition.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, long partitionKey, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, int64 partitionKey, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.Int64,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, partitionKey As Long, timeout As TimeSpan) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * int64 * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Service Fabric-Name der Dienstinstanz.</para>
        </param>
        <param name="partitionKey">
          <para>Der Partitionsschlüssel für die Dienstpartition.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <summary>
          <para>Fragt das System für die Sammlung von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </summary>
        <returns>
          <para>Der Satz von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </returns>
        <remarks>
          <para>Dies ist eine Beschwerde-basierten Lösung API.</para>
          <para>Dadurch wird zurückgegeben, eine <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Partition angegebenen Dienst. Wenn diese Überladung verwendet wird, das System gibt stets den am nächsten gelegenen <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Dienstpartition.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, string partitionKey, System.Fabric.ResolvedServicePartition previousResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, string partitionKey, class System.Fabric.ResolvedServicePartition previousResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.String,System.Fabric.ResolvedServicePartition)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, partitionKey As String, previousResult As ResolvedServicePartition) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * string * System.Fabric.ResolvedServicePartition -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey, previousResult)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="previousResult" Type="System.Fabric.ResolvedServicePartition" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Service Fabric-Name der Dienstinstanz.</para>
        </param>
        <param name="partitionKey">
          <para>Der Partitionsschlüssel für die Dienstpartition.</para>
        </param>
        <param name="previousResult">
          <para>Der vorherige <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Dienstpartition, die der Benutzer annimmt, veraltet ist.</para>
        </param>
        <summary>
          <para>Fragt das System für die Sammlung von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </summary>
        <returns>
          <para>Der Satz von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </returns>
        <remarks>
          <para>Dies ist eine Beschwerde-basierten Lösung API.</para>
          <para>Dadurch wird zurückgegeben, eine <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Partition angegebenen Dienst. Wenn diese Überladung verwendet wird, wird das System einen aktuelleren zurückgeben <see cref="T:System.Fabric.ResolvedServicePartition" /> als das Argument "PreviousResult", sofern dieser verfügbar ist.</para>
          <para>Das Argument PreviousResult ermöglicht dem Benutzer sagen: "This der vorherigen Liste der Endpunkte für diese Partition Service is. Ich habe die Endpunkte, und ich davon ausgehen, dass sie veraltet sind. Zurückgeben Sie mir eine aktuellere Version dieser Menge". Das System in diesem Fall versucht, einen aktuelleren zurückzusetzen <see cref="T:System.Fabric.ResolvedServicePartition" /> in die möglichst effiziente Weise ausgeführt. Wenn keine neuere Version nicht gefunden werden kann, eine <see cref="T:System.Fabric.ResolvedServicePartition" /> mit der gleichen Version zurückgegeben. ResolveServicePartition kann ohne PreviousResult Argument auf null festgelegt ist oder PreviousResult Argument aufgerufen werden. Wie keine Voraussetzung angegeben wird, wird das System die nächstgelegene Kopie zurückgeben der <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Dienstpartition.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, string partitionKey, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, string partitionKey, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.String,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, partitionKey As String, timeout As TimeSpan) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * string * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Service Fabric-Name der Dienstinstanz.</para>
        </param>
        <param name="partitionKey">
          <para>Der Partitionsschlüssel für die Dienstpartition.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <summary>
          <para>Fragt das System für die Sammlung von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </summary>
        <returns>
          <para>Der Satz von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </returns>
        <remarks>
          <para>Dies ist eine Beschwerde-basierten Lösung API.</para>
          <para>Dadurch wird zurückgegeben, eine <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Partition angegebenen Dienst. Wenn diese Überladung verwendet wird, das System gibt stets den am nächsten gelegenen <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Dienstpartition.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Service Fabric-Name der Dienstinstanz.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Fragt das System für die Sammlung von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </summary>
        <returns>
          <para>Der Satz von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </returns>
        <remarks>
          <para>Dies ist eine Beschwerde-basierten Lösung API.</para>
          <para>Dadurch wird zurückgegeben, eine <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Partition angegebenen Dienst. Wenn diese Überladung verwendet wird, das System gibt stets den am nächsten gelegenen <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Dienstpartition.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, System.Fabric.ResolvedServicePartition previousResult, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, class System.Fabric.ResolvedServicePartition previousResult, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.Fabric.ResolvedServicePartition,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * System.Fabric.ResolvedServicePartition * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, previousResult, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="previousResult" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Service Fabric-Name der Dienstinstanz.</para>
        </param>
        <param name="previousResult">
          <para>Vorherige <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Dienstpartition, die der Benutzer annimmt, veraltet ist.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" />, die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Fragt das System für die Sammlung von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </summary>
        <returns>
          <para>Der Satz von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </returns>
        <remarks>
          <para>Dies ist eine Beschwerde-basierten Lösung API.</para>
          <para>Diese Methode zurückgegeben wird ein <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Partition angegebenen Dienst. Wenn diese Überladung verwendet wird, wird das System einen aktuelleren zurückgeben <see cref="T:System.Fabric.ResolvedServicePartition" /> als das Argument "PreviousResult", sofern dieser verfügbar ist.</para>
          <para>
            <paramref name="previousResult" />Argument ermöglicht dem Benutzer sagen: "This der vorherigen Liste der Endpunkte für diese Partition Service is. Ich habe die Endpunkte, und ich davon ausgehen, dass sie veraltet sind. Zurückgeben Sie mir eine aktuellere Version dieser Menge". Das System in diesem Fall versucht, einen aktuelleren zurückzusetzen <see cref="T:System.Fabric.ResolvedServicePartition" /> in die möglichst effiziente Weise ausgeführt. Wenn keine neuere Version nicht gefunden werden kann, eine <see cref="T:System.Fabric.ResolvedServicePartition" /> mit der gleichen Version zurückgegeben. ResolveServicePartition aufgerufen werden kann, ohne die <paramref name="previousResult" /> Argument oder <paramref name="previousResult" /> Argument auf null festgelegt ist. Wie keine Voraussetzung angegeben wird, wird das System die nächstgelegene Kopie zurückgeben der <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Dienstpartition.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, long partitionKey, System.Fabric.ResolvedServicePartition previousResult, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, int64 partitionKey, class System.Fabric.ResolvedServicePartition previousResult, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.Int64,System.Fabric.ResolvedServicePartition,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, partitionKey As Long, previousResult As ResolvedServicePartition, timeout As TimeSpan) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * int64 * System.Fabric.ResolvedServicePartition * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey, previousResult, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.Int64" />
        <Parameter Name="previousResult" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Service Fabric-Name der Dienstinstanz.</para>
        </param>
        <param name="partitionKey">
          <para>Der Partitionsschlüssel für die Dienstpartition.</para>
        </param>
        <param name="previousResult">
          <para>Vorherige <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Dienstpartition, die der Benutzer annimmt, veraltet ist.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <summary>
          <para>Fragt das System für die Sammlung von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </summary>
        <returns>
          <para>Der Satz von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </returns>
        <remarks>
          <para>Dies ist eine Beschwerde-basierten Lösung API.</para>
          <para>Dadurch wird zurückgegeben, eine <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Partition angegebenen Dienst. Wenn diese Überladung verwendet wird, wird das System einen aktuelleren zurückgeben <see cref="T:System.Fabric.ResolvedServicePartition" /> als das Argument "PreviousResult", sofern dieser verfügbar ist.</para>
          <para>PreviousResult Argument ermöglicht dem Benutzer sagen: "This der vorherigen Liste der Endpunkte für diese Partition Service is. Ich habe die Endpunkte, und ich davon ausgehen, dass sie veraltet sind. Zurückgeben Sie mir eine aktuellere Version dieser Menge". Das System in diesem Fall versucht, einen aktuelleren zurückzusetzen <see cref="T:System.Fabric.ResolvedServicePartition" /> in die möglichst effiziente Weise ausgeführt. Wenn keine neuere Version nicht gefunden werden kann, eine <see cref="T:System.Fabric.ResolvedServicePartition" /> mit der gleichen Version zurückgegeben. ResolveServicePartition kann ohne PreviousResult Argument auf null festgelegt ist oder PreviousResult Argument aufgerufen werden. Wie keine Voraussetzung angegeben wird, wird das System die nächstgelegene Kopie zurückgeben der <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Dienstpartition.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, long partitionKey, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, int64 partitionKey, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Service Fabric-Name der Dienstinstanz.</para>
        </param>
        <param name="partitionKey">
          <para>Der Partitionsschlüssel für die Dienstpartition.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Fragt das System für die Sammlung von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </summary>
        <returns>
          <para>Der Satz von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </returns>
        <remarks>
          <para>Dies ist eine Beschwerde-basierten Lösung API.</para>
          <para>Dadurch wird zurückgegeben, eine <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Partition angegebenen Dienst. Wenn diese Überladung verwendet wird, das System gibt stets den am nächsten gelegenen <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Dienstpartition.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, string partitionKey, System.Fabric.ResolvedServicePartition previousResult, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, string partitionKey, class System.Fabric.ResolvedServicePartition previousResult, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.String,System.Fabric.ResolvedServicePartition,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="Public Function ResolveServicePartitionAsync (serviceName As Uri, partitionKey As String, previousResult As ResolvedServicePartition, timeout As TimeSpan) As Task(Of ResolvedServicePartition)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * string * System.Fabric.ResolvedServicePartition * TimeSpan -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey, previousResult, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="previousResult" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Service Fabric-Name der Dienstinstanz.</para>
        </param>
        <param name="partitionKey">
          <para>Der Partitionsschlüssel für die Dienstpartition.</para>
        </param>
        <param name="previousResult">
          <para>Der vorherige <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Dienstpartition, die der Benutzer annimmt, veraltet ist.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <summary>
          <para>Fragt das System für die Sammlung von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </summary>
        <returns>
          <para>Der Satz von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </returns>
        <remarks>
          <para>Dies ist eine Beschwerde-basierten Lösung API.</para>
          <para>Dadurch wird zurückgegeben, eine <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Partition angegebenen Dienst. Wenn diese Überladung verwendet wird, wird das System einen aktuelleren zurückgeben <see cref="T:System.Fabric.ResolvedServicePartition" /> als das Argument "PreviousResult", sofern dieser verfügbar ist.</para>
          <para>Das Argument PreviousResult ermöglicht dem Benutzer sagen: "This der vorherigen Liste der Endpunkte für diese Partition Service is. Ich habe die Endpunkte, und ich davon ausgehen, dass sie veraltet sind. Zurückgeben Sie mir eine aktuellere Version dieser Menge". Das System in diesem Fall versucht, einen aktuelleren zurückzusetzen <see cref="T:System.Fabric.ResolvedServicePartition" /> in die möglichst effiziente Weise ausgeführt. Wenn keine neuere Version nicht gefunden werden kann, eine <see cref="T:System.Fabric.ResolvedServicePartition" /> mit der gleichen Version zurückgegeben. ResolveServicePartition kann ohne PreviousResult Argument auf null festgelegt ist oder PreviousResult Argument aufgerufen werden. Wie keine Voraussetzung angegeben wird, wird das System die nächstgelegene Kopie zurückgeben der <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Dienstpartition.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, string partitionKey, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, string partitionKey, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.String,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * string * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Service Fabric-Name der Dienstinstanz.</para>
        </param>
        <param name="partitionKey">
          <para>Der Partitionsschlüssel für die Dienstpartition.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Fragt das System für die Sammlung von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </summary>
        <returns>
          <para>Der Satz von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </returns>
        <remarks>
          <para>Dies ist eine Beschwerde-basierten Lösung API.</para>
          <para>Dadurch wird zurückgegeben, eine <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Partition angegebenen Dienst. Wenn diese Überladung verwendet wird, das System gibt stets den am nächsten gelegenen <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Dienstpartition.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, long partitionKey, System.Fabric.ResolvedServicePartition previousResult, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, int64 partitionKey, class System.Fabric.ResolvedServicePartition previousResult, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.Int64,System.Fabric.ResolvedServicePartition,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * int64 * System.Fabric.ResolvedServicePartition * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey, previousResult, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.Int64" />
        <Parameter Name="previousResult" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Service Fabric-Name der Dienstinstanz.</para>
        </param>
        <param name="partitionKey">
          <para>Der Partitionsschlüssel für die Dienstpartition.</para>
        </param>
        <param name="previousResult">
          <para>Vorherige <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Dienstpartition, die der Benutzer annimmt, veraltet ist.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>
            <see cref="T:System.Threading.CancellationToken" />dass der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Fragt das System für die Sammlung von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </summary>
        <returns>
          <para>Der Satz von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </returns>
        <remarks>
          <para>Dies ist eine Beschwerde-basierten Lösung API.</para>
          <para>Dadurch wird zurückgegeben, eine <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Partition angegebenen Dienst. Wenn diese Überladung verwendet wird, wird das System einen aktuelleren zurückgeben <see cref="T:System.Fabric.ResolvedServicePartition" /> als das Argument "PreviousResult", sofern dieser verfügbar ist.</para>
          <para>PreviousResult Argument ermöglicht dem Benutzer sagen: "This der vorherigen Liste der Endpunkte für diese Partition Service is. Ich habe die Endpunkte, und ich davon ausgehen, dass sie veraltet sind. Zurückgeben Sie mir eine aktuellere Version dieser Menge". Das System in diesem Fall versucht, einen aktuelleren zurückzusetzen <see cref="T:System.Fabric.ResolvedServicePartition" /> in die möglichst effiziente Weise ausgeführt. Wenn keine neuere Version nicht gefunden werden kann, eine <see cref="T:System.Fabric.ResolvedServicePartition" /> mit der gleichen Version zurückgegeben. ResolveServicePartition kann ohne PreviousResult Argument auf null festgelegt ist oder PreviousResult Argument aufgerufen werden. Wie keine Voraussetzung angegeben wird, wird das System die nächstgelegene Kopie zurückgeben der <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Dienstpartition.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="ResolveServicePartitionAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync (Uri serviceName, string partitionKey, System.Fabric.ResolvedServicePartition previousResult, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Fabric.ResolvedServicePartition&gt; ResolveServicePartitionAsync(class System.Uri serviceName, string partitionKey, class System.Fabric.ResolvedServicePartition previousResult, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.ResolveServicePartitionAsync(System.Uri,System.String,System.Fabric.ResolvedServicePartition,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.ResolveServicePartitionAsync : Uri * string * System.Fabric.ResolvedServicePartition * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;" Usage="serviceManagementClient.ResolveServicePartitionAsync (serviceName, partitionKey, previousResult, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ResolvedServicePartition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="serviceName" Type="System.Uri" />
        <Parameter Name="partitionKey" Type="System.String" />
        <Parameter Name="previousResult" Type="System.Fabric.ResolvedServicePartition" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="serviceName">
          <para>Der Service Fabric-Name der Dienstinstanz.</para>
        </param>
        <param name="partitionKey">
          <para>Der Partitionsschlüssel für die Dienstpartition.</para>
        </param>
        <param name="previousResult">
          <para>Der vorherige <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Dienstpartition, die der Benutzer annimmt, veraltet ist.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Fragt das System für die Sammlung von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </summary>
        <returns>
          <para>Der Satz von Endpunkten, denen um die Partition angegebene Dienst überwacht wird.</para>
        </returns>
        <remarks>
          <para>Dies ist eine Beschwerde-basierten Lösung API.</para>
          <para>Dadurch wird zurückgegeben, eine <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Partition angegebenen Dienst. Wenn diese Überladung verwendet wird, wird das System einen aktuelleren zurückgeben <see cref="T:System.Fabric.ResolvedServicePartition" /> als das Argument "PreviousResult", sofern dieser verfügbar ist.</para>
          <para>Das Argument PreviousResult ermöglicht dem Benutzer sagen: "This der vorherigen Liste der Endpunkte für diese Partition Service is. Ich habe die Endpunkte, und ich davon ausgehen, dass sie veraltet sind. Zurückgeben Sie mir eine aktuellere Version dieser Menge". Das System in diesem Fall versucht, einen aktuelleren zurückzusetzen <see cref="T:System.Fabric.ResolvedServicePartition" /> in die möglichst effiziente Weise ausgeführt. Wenn keine neuere Version nicht gefunden werden kann, eine <see cref="T:System.Fabric.ResolvedServicePartition" /> mit der gleichen Version zurückgegeben. ResolveServicePartition kann ohne PreviousResult Argument auf null festgelegt ist oder PreviousResult Argument aufgerufen werden. Wie keine Voraussetzung angegeben wird, wird das System die nächstgelegene Kopie zurückgeben der <see cref="T:System.Fabric.ResolvedServicePartition" /> für die Dienstpartition.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="RestartReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestartReplicaAsync (string nodeName, Guid partitionId, long replicaOrInstanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RestartReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaOrInstanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RestartReplicaAsync(System.String,System.Guid,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function RestartReplicaAsync (nodeName As String, partitionId As Guid, replicaOrInstanceId As Long) As Task" />
      <MemberSignature Language="F#" Value="member this.RestartReplicaAsync : string * Guid * int64 -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.RestartReplicaAsync (nodeName, partitionId, replicaOrInstanceId)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaOrInstanceId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des Knotens.</para>
        </param>
        <param name="partitionId">
          <para>Die Partitions-ID.</para>
        </param>
        <param name="replicaOrInstanceId">
          <para>Der Instanzbezeichner.</para>
        </param>
        <summary>
          <para>Startet ein Dienstreplikat eines permanenten Diensts neu, das auf einem Knoten ausgeführt wird.</para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die die Bestätigung der Anforderung darstellt.</para>
        </returns>
        <remarks>
          <para>Warnung: Es werden keine sicherheitsüberprüfungen ausgeführt, wenn diese API verwendet wird. Eine falsche Verwendung dieser API kann zum Verlust der Verfügbarkeit von zustandsbehafteten Diensten führen.</para>
          <para>Der Standardtimeout beträgt eine Minute für die lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ReplicaDoesNotExist" />wird zurückgegeben, wenn das Replikat oder eine Instanz-Id auf dem Knoten nicht ausgeführt wird.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaStateForReplicaOperation" />wird zurückgegeben, wenn das Replikat oder eine Instanz-Id kann nicht neu gestartet oder zu diesem Zeitpunkt entfernt werden, da sie einen ungültigen Status aufweist. Beispielsweise wird das Replikat bereits gerade geschlossen wird.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaOperation" />wird zurückgegeben, wenn das Replikat nicht mit einem zustandsbehafteten persistente Dienst gehört. Nur können zustandsbehaftete persistente Replikate neu gestartet werden.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.ArgumentException">Wenn <paramref name="nodeName" /> ist null oder leer.</exception>
      </Docs>
    </Member>
    <Member MemberName="RestartReplicaAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestartReplicaAsync (string nodeName, Guid partitionId, long replicaOrInstanceId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task RestartReplicaAsync(string nodeName, valuetype System.Guid partitionId, int64 replicaOrInstanceId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.RestartReplicaAsync(System.String,System.Guid,System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.RestartReplicaAsync : string * Guid * int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.RestartReplicaAsync (nodeName, partitionId, replicaOrInstanceId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nodeName" Type="System.String" />
        <Parameter Name="partitionId" Type="System.Guid" />
        <Parameter Name="replicaOrInstanceId" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nodeName">
          <para>Der Name des Knotens.</para>
        </param>
        <param name="partitionId">
          <para>Die Partitions-ID.</para>
        </param>
        <param name="replicaOrInstanceId">
          <para>Der Instanzbezeichner.</para>
        </param>
        <param name="timeout">
          <para>Die Zeitspanne, die die maximale Zeitdauer definiert können diesen Vorgang fortzusetzen, vor der Rückgabe eine <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das optionale Abbruchtoken, das beobachten von der Vorgang. Es kann verwendet werden, um eine Benachrichtigung zu senden, dass der Vorgang abgebrochen werden soll. Beachten Sie, dass Abbruch advisory ist und die der Vorgang weiterhin ausgeführt werden kann, selbst wenn er abgebrochen wird.</para>
        </param>
        <summary>
          <para>Startet ein Dienstreplikat eines permanenten Diensts neu, das auf einem Knoten ausgeführt wird.
            Nimmt auch in Timeoutintervall, was die maximal zulässige Zeit das System diesen Vorgang fortzusetzen lässt, vor der Rückgabe <see cref="T:System.TimeoutException" /> und Abbruchtoken, das beobachten von der Vorgang. 
            </para>
        </summary>
        <returns>
          <para>Eine Aufgabe, die die Bestätigung der Anforderung darstellt.</para>
        </returns>
        <remarks>
          <para>Warnung: Es werden keine sicherheitsüberprüfungen ausgeführt, wenn diese API verwendet wird. Eine falsche Verwendung dieser API kann zum Verlust der Verfügbarkeit von zustandsbehafteten Diensten führen.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ReplicaDoesNotExist" />wird zurückgegeben, wenn das Replikat oder eine Instanz-Id auf dem Knoten nicht ausgeführt wird.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaStateForReplicaOperation" />wird zurückgegeben, wenn das Replikat oder eine Instanz-Id kann nicht neu gestartet oder zu diesem Zeitpunkt entfernt werden, da sie einen ungültigen Status aufweist. Beispielsweise wird das Replikat bereits gerade geschlossen wird.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidReplicaOperation" />wird zurückgegeben, wenn das Replikat nicht mit einem zustandsbehafteten persistente Dienst gehört. Nur können zustandsbehaftete persistente Replikate neu gestartet werden.</para>
          <para>
                Siehe auch <see href="https://docs.microsoft.com/en-us/azure/service-fabric/service-fabric-errors-and-exceptions" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
        <exception cref="T:System.ArgumentException">Wenn <paramref name="nodeName" /> ist null oder leer.</exception>
      </Docs>
    </Member>
    <Member MemberName="ServiceNotificationFilterMatched">
      <MemberSignature Language="C#" Value="public event EventHandler ServiceNotificationFilterMatched;" />
      <MemberSignature Language="ILAsm" Value=".event class System.EventHandler ServiceNotificationFilterMatched" />
      <MemberSignature Language="DocId" Value="E:System.Fabric.FabricClient.ServiceManagementClient.ServiceNotificationFilterMatched" />
      <MemberSignature Language="VB.NET" Value="Public Event ServiceNotificationFilterMatched As EventHandler " />
      <MemberSignature Language="F#" Value="member this.ServiceNotificationFilterMatched : EventHandler " Usage="member this.ServiceNotificationFilterMatched : System.EventHandler " />
      <MemberType>Event</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.EventHandler</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
          <para>Wird ausgelöst, wenn eine <see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" /> über zuvor registrierten <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" /> anhand des Diensts endpunktänderungen abgeglichen wird, die im System.</para>
        </summary>
        <remarks>
            Das Ereignisargument ist vom Typ <see cref="T:System.Fabric.FabricClient.ServiceManagementClient.ServiceNotificationEventArgs" />.
            </remarks>
        <example>
            Das folgende Beispiel zeigt, wie zum Registrieren für und -Benachrichtigungen zu verarbeiten:
            <code language="cs">
            namespace ServiceNotificationsExample
            {
                class Program
                {
                    static void Main(string[] args)
                    {
                        var client = new FabricClient(new string[] { "[cluster_endpoint]:[client_port]" });
            
                        var filter = new ServiceNotificationFilterDescription()
                        {
                            Name = new Uri("fabric:/my_application"),
                            MatchNamePrefix = true,
                        };
            
                        client.ServiceManager.ServiceNotificationFilterMatched += (s, e) =&gt; OnNotification(e);
            
                        var filterId = client.ServiceManager.RegisterServiceNotificationFilterAsync(filter).Result;
            
                        Console.WriteLine(
                            "Registered filter: name={0} id={1}",
                            filter.Name,
                            filterId);
            
                        Console.ReadLine();
            
                        client.ServiceManager.UnregisterServiceNotificationFilterAsync(filterId).Wait();
            
                        Console.WriteLine(
                            "Unregistered filter: name={0} id={1}",
                            filter.Name,
                            filterId);
                    }
            
                    private static void OnNotification(EventArgs e)
                    {
                        var castedEventArgs = (FabricClient.ServiceManagementClient.ServiceNotificationEventArgs)e;
            
                        var notification = castedEventArgs.Notification;
            
                        Console.WriteLine(
                            "[{0}] received notification for service '{1}'",
                            DateTime.UtcNow,
                            notification.ServiceName);
                    }
                }
            }
            </code></example>
      </Docs>
    </Member>
    <Member MemberName="UnregisterServiceNotificationFilterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnregisterServiceNotificationFilterAsync (long filterId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnregisterServiceNotificationFilterAsync(int64 filterId) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.UnregisterServiceNotificationFilterAsync(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Function UnregisterServiceNotificationFilterAsync (filterId As Long) As Task" />
      <MemberSignature Language="F#" Value="member this.UnregisterServiceNotificationFilterAsync : int64 -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.UnregisterServiceNotificationFilterAsync filterId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filterId" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="filterId">
          <para>Die ID eines zuvor registrierten <see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" /> Merry <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" />.</para>
        </param>
        <summary>
          <para>Hebt die Registrierung eines zuvor registrierten <see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , das den asynchronen Vorgang darstellt.</para>
        </returns>
        <remarks>
          <para>Es ist nicht notwendig, einzelne Filter aufgehoben, wenn der Client selbst nicht mehr soll, da alle verwendet werden <see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" /> Objekte registriert, indem Sie die <see cref="T:System.Fabric.FabricClient" /> wird automatisch aufgehoben werden, wenn ein Client freigegeben wird.</para>
          <para>Der Standardtimeout beträgt eine Minute für die lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterServiceNotificationFilterAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UnregisterServiceNotificationFilterAsync (long filterId, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UnregisterServiceNotificationFilterAsync(int64 filterId, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.UnregisterServiceNotificationFilterAsync(System.Int64,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UnregisterServiceNotificationFilterAsync : int64 * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.UnregisterServiceNotificationFilterAsync (filterId, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filterId" Type="System.Int64" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="filterId">
          <para>Die ID eines zuvor registrierten <see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" /> Merry <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServiceNotificationFilterAsync(System.Fabric.Description.ServiceNotificationFilterDescription)" />.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeit zum Verarbeiten der Anforderung vor zulässig <see cref="T:System.TimeoutException" /> ausgelöst wird.</para>
        </param>
        <param name="cancellationToken">
          <para>Für zukünftige Verwendung reserviert.</para>
        </param>
        <summary>
          <para>Hebt die Registrierung eines zuvor registrierten <see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" />.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , das den asynchronen Vorgang darstellt.</para>
        </returns>
        <remarks>
            Es ist nicht notwendig, einzelne Filter aufgehoben, wenn der Client selbst nicht mehr soll, da alle verwendet werden <see cref="T:System.Fabric.Description.ServiceNotificationFilterDescription" /> Objekte registriert, indem Sie die <see cref="T:System.Fabric.FabricClient" /> wird automatisch aufgehoben werden, wenn ein Client freigegeben wird.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterServicePartitionResolutionChangeHandler">
      <MemberSignature Language="C#" Value="public void UnregisterServicePartitionResolutionChangeHandler (long callbackHandle);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void UnregisterServicePartitionResolutionChangeHandler(int64 callbackHandle) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.UnregisterServicePartitionResolutionChangeHandler(System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub UnregisterServicePartitionResolutionChangeHandler (callbackHandle As Long)" />
      <MemberSignature Language="F#" Value="member this.UnregisterServicePartitionResolutionChangeHandler : int64 -&gt; unit" Usage="serviceManagementClient.UnregisterServicePartitionResolutionChangeHandler callbackHandle" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>System.Fabric</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callbackHandle" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="callbackHandle">
          <para>Der CallbackHandle-Bezeichner, der entfernt werden. Dies wird zurückgegeben, durch die <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServicePartitionResolutionChangeHandler(System.Uri,System.Fabric.ServicePartitionResolutionChangeHandler)" /> aufrufen.</para>
        </param>
        <summary>
          <para>Hebt die Registrierung eines Änderung Handlers mit zuvor registrierten <see cref="M:System.Fabric.FabricClient.ServiceManagementClient.RegisterServicePartitionResolutionChangeHandler(System.Uri,System.Fabric.ServicePartitionResolutionChangeHandler)" />.</para>
        </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateServiceAsync (Uri name, System.Fabric.Description.ServiceUpdateDescription updateDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateServiceAsync(class System.Uri name, class System.Fabric.Description.ServiceUpdateDescription updateDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateServiceAsync (name As Uri, updateDescription As ServiceUpdateDescription) As Task" />
      <MemberSignature Language="F#" Value="member this.UpdateServiceAsync : Uri * System.Fabric.Description.ServiceUpdateDescription -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.UpdateServiceAsync (name, updateDescription)" />
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
        <Parameter Name="updateDescription" Type="System.Fabric.Description.ServiceUpdateDescription" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>Der Name der URI des Diensts aktualisiert wird.</para>
        </param>
        <param name="updateDescription">
          <para>Die <see cref="T:System.Fabric.Description.ServiceUpdateDescription" /> , die die aktualisierte Konfiguration für den Dienst angibt.</para>
        </param>
        <summary>
          <para>Aktualisiert einen Dienst mit der angegebenen Beschreibung.</para>
        </summary>
        <returns>
          <para>Der aktualisierte Dienst.</para>
        </returns>
        <remarks>
          <para>Der Standardtimeout beträgt eine Minute für die lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />. </para>
          <para>Hinweis: Auf sichere Weise beide erhöht die <see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.MinReplicaSetSize" /> und <see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.TargetReplicaSetSize" /> zuerst erhöhen die <see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.TargetReplicaSetSize" /> und warten Sie, zusätzliche Replikate erstellt werden, und klicken Sie dann erhöhen die<see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.MinReplicaSetSize" /></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".
            Löschen Sie die<see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">Wenn <paramref name="name" /> oder <paramref name="updateDescription" /> NULL sind.</exception>
      </Docs>
    </Member>
    <Member MemberName="UpdateServiceAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task UpdateServiceAsync (Uri name, System.Fabric.Description.ServiceUpdateDescription serviceUpdateDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task UpdateServiceAsync(class System.Uri name, class System.Fabric.Description.ServiceUpdateDescription serviceUpdateDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:System.Fabric.FabricClient.ServiceManagementClient.UpdateServiceAsync(System.Uri,System.Fabric.Description.ServiceUpdateDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.UpdateServiceAsync : Uri * System.Fabric.Description.ServiceUpdateDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="serviceManagementClient.UpdateServiceAsync (name, serviceUpdateDescription, timeout, cancellationToken)" />
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
        <Parameter Name="serviceUpdateDescription" Type="System.Fabric.Description.ServiceUpdateDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="name">
          <para>Der Name der URI des Diensts aktualisiert wird.</para>
        </param>
        <param name="serviceUpdateDescription">
          <para>Die <see cref="T:System.Fabric.Description.ServiceUpdateDescription" /> , die die aktualisierte Konfiguration für den Dienst angibt.</para>
        </param>
        <param name="timeout">
          <para>Die maximale Zeitdauer lässt das System diesen Vorgang fortzusetzen, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Aktualisiert einen Dienst mit der angegebenen Beschreibung.
            Nimmt auch in Timeoutintervall, was die maximal zulässige Zeit das System diesen Vorgang fortzusetzen lässt, vor der Rückgabe <see cref="T:System.TimeoutException" /> und Abbruchtoken, das beobachten von der Vorgang. 
            </para>
        </summary>
        <returns>
          <para>Der aktualisierte Dienst.</para>
        </returns>
        <remarks>
          <para>Hinweis: Auf sichere Weise beide erhöht die <see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.MinReplicaSetSize" /> und <see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.TargetReplicaSetSize" /> zuerst erhöhen die <see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.TargetReplicaSetSize" /> und warten Sie, zusätzliche Replikate erstellt werden, und klicken Sie dann erhöhen die<see cref="P:System.Fabric.Description.StatefulServiceUpdateDescription.MinReplicaSetSize" /></para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen".
            Löschen Sie die<see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.ArgumentNullException">Wenn <paramref name="name" /> oder <paramref name="serviceUpdateDescription" /> NULL sind.</exception>
      </Docs>
    </Member>
  </Members>
</Type>