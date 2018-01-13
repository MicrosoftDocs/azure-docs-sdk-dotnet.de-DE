<Type Name="Extensions" FullName="Microsoft.ServiceFabric.Preview.Client.Extensions">
  <TypeSignature Language="C#" Value="public static class Extensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit Extensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Preview.Client.Extensions" />
  <TypeSignature Language="VB.NET" Value="Public Module Extensions" />
  <TypeSignature Language="F#" Value="type Extensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für FabricClient.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CreateComposeDeploymentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CreateComposeDeploymentAsync (this System.Fabric.FabricClient.ComposeDeploymentClient client, Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription composeDeploymentDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CreateComposeDeploymentAsync(class System.Fabric.FabricClient/ComposeDeploymentClient client, class Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription composeDeploymentDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.CreateComposeDeploymentAsync(System.Fabric.FabricClient.ComposeDeploymentClient,Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription)" />
      <MemberSignature Language="F#" Value="static member CreateComposeDeploymentAsync : System.Fabric.FabricClient.ComposeDeploymentClient * Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription -&gt; System.Threading.Tasks.Task" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.CreateComposeDeploymentAsync (client, composeDeploymentDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+ComposeDeploymentClient" RefType="this" />
        <Parameter Name="composeDeploymentDescription" Type="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" />
      </Parameters>
      <Docs>
        <param name="client">
          <see cref="T:System.Fabric.FabricClient" />-Objekt</param>
        <param name="composeDeploymentDescription">
          <para>Die <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" /> , beschreibt die Compose-Bereitstellung erstellt werden.</para>
        </param>
        <summary>
          <para>Erstellt und instanziiert die Service Fabric verfassen-Bereitstellung, die von der Beschreibung der Compose-Bereitstellung beschrieben.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />: Die erstellungsanforderung für die Anwendung ist ungültig in Bezug auf die bereitgestellten Bereitstellungsmanifeste für die angeforderte Anwendungstyp.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: Der Anwendungsname ist kein gültiger Naming URI.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: Eine beschädigte Datei wurde auf der Image Store gefunden.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ComposeDeploymentAlreadyExists" />: Die Compose-Bereitstellung wurde bereits erstellt.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationAlreadyExists" />: Die Anwendung wurde bereits erstellt, damit die Bereitstellung zusammensetzen kann nicht mit dem gleichen Namen erstellt werden. </para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Fehler bei der Zugriff auf eine Datei auf den Imagespeicher besitzen.</para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para>Eine erforderliche Datei wurde nicht gefunden.</para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para>Ein Pfad zu einem Image Store Datei/Verzeichnis war zu lang.</para>
        </exception>
        <exception cref="T:System.IO.IOException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den Imagespeicher besitzen.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
                Die Parameter angegeben wird, über die <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" /> sind falsch.
              </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateComposeDeploymentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CreateComposeDeploymentAsync (this System.Fabric.FabricClient.ComposeDeploymentClient client, Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription composeDeploymentDescription, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CreateComposeDeploymentAsync(class System.Fabric.FabricClient/ComposeDeploymentClient client, class Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription composeDeploymentDescription, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.CreateComposeDeploymentAsync(System.Fabric.FabricClient.ComposeDeploymentClient,Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription,System.TimeSpan)" />
      <MemberSignature Language="F#" Value="static member CreateComposeDeploymentAsync : System.Fabric.FabricClient.ComposeDeploymentClient * Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.CreateComposeDeploymentAsync (client, composeDeploymentDescription, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+ComposeDeploymentClient" RefType="this" />
        <Parameter Name="composeDeploymentDescription" Type="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="client">
          <see cref="T:System.Fabric.FabricClient" />-Objekt</param>
        <param name="composeDeploymentDescription">
          <para>Die <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" /> , beschreibt die Compose-Bereitstellung erstellt werden.</para>
        </param>
        <param name="timeout">
          <para>Definiert die maximale Zeitspanne, das System diesen Vorgang fortzusetzen lässt, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <summary>
          <para>Erstellt und instanziiert die Service Fabric verfassen-Bereitstellung, die von der Beschreibung der Compose-Bereitstellung beschrieben.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />: Die erstellungsanforderung für die Anwendung ist ungültig in Bezug auf die bereitgestellten Bereitstellungsmanifeste für die angeforderte Anwendungstyp.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: Der Anwendungsname ist kein gültiger Naming URI.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: Eine beschädigte Datei wurde auf der Image Store gefunden.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ComposeDeploymentAlreadyExists" />: Die Compose-Bereitstellung wurde bereits erstellt.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationAlreadyExists" />: Die Anwendung wurde bereits erstellt, damit die Bereitstellung zusammensetzen kann nicht mit dem gleichen Namen erstellt werden. </para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Fehler bei der Zugriff auf eine Datei auf den Imagespeicher besitzen.</para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para>Auf der Image Store ist eine erforderliche Datei nicht gefunden.</para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para>Ein erforderliches Verzeichnis wurde auf der Image Store nicht gefunden.</para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para>Ein Pfad zu einem Image Store Datei/Verzeichnis war zu lang.</para>
        </exception>
        <exception cref="T:System.IO.IOException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den Imagespeicher besitzen.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
                Die Parameter angegeben wird, über die <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" /> sind falsch.
              </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="CreateComposeDeploymentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task CreateComposeDeploymentAsync (this System.Fabric.FabricClient.ComposeDeploymentClient client, Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription composeDeploymentDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task CreateComposeDeploymentAsync(class System.Fabric.FabricClient/ComposeDeploymentClient client, class Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription composeDeploymentDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.CreateComposeDeploymentAsync(System.Fabric.FabricClient.ComposeDeploymentClient,Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateComposeDeploymentAsync : System.Fabric.FabricClient.ComposeDeploymentClient * Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.CreateComposeDeploymentAsync (client, composeDeploymentDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+ComposeDeploymentClient" RefType="this" />
        <Parameter Name="composeDeploymentDescription" Type="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="client">
          <see cref="T:System.Fabric.FabricClient" />-Objekt</param>
        <param name="composeDeploymentDescription">
          <para>Die <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" /> , beschreibt die Compose-Bereitstellung erstellt werden.</para>
        </param>
        <param name="timeout">
          <para>Definiert die maximale Zeitspanne, das System diesen Vorgang fortzusetzen lässt, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das CancellationToken, das beobachten von der Vorgang. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Erstellt und instanziiert die Service Fabric verfassen-Bereitstellung, die von der Beschreibung der Compose-Bereitstellung beschrieben.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageBuilderValidationError" />: Die erstellungsanforderung für die Anwendung ist ungültig in Bezug auf die bereitgestellten Bereitstellungsmanifeste für die angeforderte Anwendungstyp.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.InvalidNameUri" />: Der Anwendungsname ist kein gültiger Naming URI.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.CorruptedImageStoreObjectFound" />: Eine beschädigte Datei wurde auf der Image Store gefunden.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementAlreadyExistsException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ComposeDeploymentAlreadyExists" />: Die Compose-Bereitstellung wurde bereits erstellt.</para>
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationAlreadyExists" />: Die Anwendung wurde bereits erstellt, damit die Bereitstellung zusammensetzen kann nicht mit dem gleichen Namen erstellt werden. </para>
        </exception>
        <exception cref="T:System.UnauthorizedAccessException">
          <para>Fehler bei der Zugriff auf eine Datei auf den Imagespeicher besitzen.</para>
        </exception>
        <exception cref="T:System.IO.FileNotFoundException">
          <para>Auf der Image Store ist eine erforderliche Datei nicht gefunden.</para>
        </exception>
        <exception cref="T:System.IO.DirectoryNotFoundException">
          <para>Ein erforderliches Verzeichnis wurde auf der Image Store nicht gefunden.</para>
        </exception>
        <exception cref="T:System.IO.PathTooLongException">
          <para>Ein Pfad zu einem Image Store Datei/Verzeichnis war zu lang.</para>
        </exception>
        <exception cref="T:System.IO.IOException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ImageStoreIOException" />: Es wurde ein e/a-Fehler bei der Kommunikation mit den Imagespeicher besitzen.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
        <exception cref="T:System.ArgumentException">
          <para>
                Die Parameter angegeben wird, über die <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentDescription" /> sind falsch.
              </para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteComposeDeploymentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteComposeDeploymentAsync (this System.Fabric.FabricClient.ComposeDeploymentClient client, Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription description);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteComposeDeploymentAsync(class System.Fabric.FabricClient/ComposeDeploymentClient client, class Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription description) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.DeleteComposeDeploymentAsync(System.Fabric.FabricClient.ComposeDeploymentClient,Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteComposeDeploymentAsync (client As FabricClient.ComposeDeploymentClient, description As DeleteComposeDeploymentDescription) As Task" />
      <MemberSignature Language="F#" Value="static member DeleteComposeDeploymentAsync : System.Fabric.FabricClient.ComposeDeploymentClient * Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription -&gt; System.Threading.Tasks.Task" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.DeleteComposeDeploymentAsync (client, description)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+ComposeDeploymentClient" RefType="this" />
        <Parameter Name="description" Type="Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription" />
      </Parameters>
      <Docs>
        <param name="client">
          <see cref="T:System.Fabric.FabricClient" />-Objekt</param>
        <param name="description">
          <para>Die <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription" /> , bestimmt die Bereitstellung verfassen gelöscht werden soll.</para>
        </param>
        <summary>
          <para>Löscht die verfassen Bereitstellung-Instanz aus dem Cluster an.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>
          <para>Alle verfassen Bereitstellungszustand verloren und kann nicht wiederhergestellt werden, nachdem die Bereitstellung verfassen gelöscht wurde.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ComposeDeploymentNotFound" />: Die Compose-Bereitstellung ist nicht vorhanden.
            </para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: Die Anwendung wird aktualisiert. </para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteComposeDeploymentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteComposeDeploymentAsync (this System.Fabric.FabricClient.ComposeDeploymentClient client, Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription description, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteComposeDeploymentAsync(class System.Fabric.FabricClient/ComposeDeploymentClient client, class Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription description, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.DeleteComposeDeploymentAsync(System.Fabric.FabricClient.ComposeDeploymentClient,Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function DeleteComposeDeploymentAsync (client As FabricClient.ComposeDeploymentClient, description As DeleteComposeDeploymentDescription, timeout As TimeSpan) As Task" />
      <MemberSignature Language="F#" Value="static member DeleteComposeDeploymentAsync : System.Fabric.FabricClient.ComposeDeploymentClient * Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription * TimeSpan -&gt; System.Threading.Tasks.Task" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.DeleteComposeDeploymentAsync (client, description, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+ComposeDeploymentClient" RefType="this" />
        <Parameter Name="description" Type="Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="client">
          <see cref="T:System.Fabric.FabricClient" />-Objekt</param>
        <param name="description">
          <para>Die <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription" /> , bestimmt die Bereitstellung verfassen gelöscht werden soll.</para>
        </param>
        <param name="timeout">
          <para>Definiert die maximale Zeitspanne, die diesen Vorgang vor der Rückgabe System.TimeoutException fortgesetzt werden kann.</para>
        </param>
        <summary>
          <para>Löscht die Compose-Bereitstellung aus dem Cluster an.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>
          <para>Alle Anwendungsstatus verloren und kann nicht wiederhergestellt werden, nachdem die Anwendung gelöscht wird.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ComposeDeploymentNotFound" />: Die Compose-Bereitstellung ist nicht vorhanden.
            </para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: Die Anwendung wird aktualisiert. </para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="DeleteComposeDeploymentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteComposeDeploymentAsync (this System.Fabric.FabricClient.ComposeDeploymentClient client, Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription description, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteComposeDeploymentAsync(class System.Fabric.FabricClient/ComposeDeploymentClient client, class Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription description, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.DeleteComposeDeploymentAsync(System.Fabric.FabricClient.ComposeDeploymentClient,Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteComposeDeploymentAsync : System.Fabric.FabricClient.ComposeDeploymentClient * Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.DeleteComposeDeploymentAsync (client, description, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+ComposeDeploymentClient" RefType="this" />
        <Parameter Name="description" Type="Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="client">
          <see cref="T:System.Fabric.FabricClient" />-Objekt</param>
        <param name="description">
          <para>Die <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.DeleteComposeDeploymentDescription" /> , bestimmt die Bereitstellung verfassen gelöscht werden soll.</para>
        </param>
        <param name="timeout">
          <para>Definiert die maximale Zeitspanne, die diesen Vorgang vor der Rückgabe System.TimeoutException fortgesetzt werden kann.</para>
        </param>
        <param name="cancellationToken">
          <para>Die <see cref="T:System.Threading.CancellationToken" /> , die der Vorgang beobachtet wird. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Löscht die Compose-Bereitstellung aus dem Cluster an.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , den Vorgang darstellt.</para>
        </returns>
        <remarks>
          <para>Alle Anwendungsstatus verloren und kann nicht wiederhergestellt werden, nachdem die Anwendung gelöscht wird.</para>
        </remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ComposeDeploymentNotFound" />: Die Compose-Bereitstellung ist nicht vorhanden.
            </para>
        </exception>
        <exception cref="T:System.Fabric.FabricTransientException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ApplicationUpgradeInProgress" />: Die Anwendung wird aktualisiert. </para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetComposeDeploymentStatusPagedListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt; GetComposeDeploymentStatusPagedListAsync (this System.Fabric.FabricClient.QueryClient client, Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription composeDeploymentQueryDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt; GetComposeDeploymentStatusPagedListAsync(class System.Fabric.FabricClient/QueryClient client, class Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription composeDeploymentQueryDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.GetComposeDeploymentStatusPagedListAsync(System.Fabric.FabricClient.QueryClient,Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetComposeDeploymentStatusPagedListAsync (client As FabricClient.QueryClient, composeDeploymentQueryDescription As ComposeDeploymentStatusQueryDescription) As Task(Of ComposeDeploymentStatusList)" />
      <MemberSignature Language="F#" Value="static member GetComposeDeploymentStatusPagedListAsync : System.Fabric.FabricClient.QueryClient * Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt;" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.GetComposeDeploymentStatusPagedListAsync (client, composeDeploymentQueryDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+QueryClient" RefType="this" />
        <Parameter Name="composeDeploymentQueryDescription" Type="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" />
      </Parameters>
      <Docs>
        <param name="client">
          <see cref="T:System.Fabric.FabricClient" />-Objekt</param>
        <param name="composeDeploymentQueryDescription">
          <para>Die <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" /> , bestimmt die Bereitstellungen verfassen abgefragt werden müssen.</para>
        </param>
        <summary>
          <para>Ruft der Status der verfassen Bereitstellungen erstellt, die in der Beschreibung der Abfrage angegebenen Filtern (sofern vorhanden) entsprechen.
            Wenn die Compose-Bereitstellungen nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , die die asynchrone Abfragevorgang darstellt.
            Der Wert von TResult-Parameter ist ein <see cref="T:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList" /> , die die Liste der darstellt verfassen Bereitstellungen, die die Filtern in berücksichtigen die <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" /> und Anpassung an die Seite.
            Wenn die abfragebeschreibung für die angegebene keine entsprechende enthält, die Bereitstellungen erstellen hat, wird eine Liste von Einträgen 0 Einträge zurückgegeben.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetComposeDeploymentStatusPagedListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt; GetComposeDeploymentStatusPagedListAsync (this System.Fabric.FabricClient.QueryClient client, Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription composeDeploymentQueryDescription, TimeSpan timeout);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt; GetComposeDeploymentStatusPagedListAsync(class System.Fabric.FabricClient/QueryClient client, class Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription composeDeploymentQueryDescription, valuetype System.TimeSpan timeout) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.GetComposeDeploymentStatusPagedListAsync(System.Fabric.FabricClient.QueryClient,Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription,System.TimeSpan)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetComposeDeploymentStatusPagedListAsync (client As FabricClient.QueryClient, composeDeploymentQueryDescription As ComposeDeploymentStatusQueryDescription, timeout As TimeSpan) As Task(Of ComposeDeploymentStatusList)" />
      <MemberSignature Language="F#" Value="static member GetComposeDeploymentStatusPagedListAsync : System.Fabric.FabricClient.QueryClient * Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription * TimeSpan -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt;" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.GetComposeDeploymentStatusPagedListAsync (client, composeDeploymentQueryDescription, timeout)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+QueryClient" RefType="this" />
        <Parameter Name="composeDeploymentQueryDescription" Type="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
      </Parameters>
      <Docs>
        <param name="client">
          <see cref="T:System.Fabric.FabricClient" />-Objekt</param>
        <param name="composeDeploymentQueryDescription">
          <para>Die <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" /> , bestimmt die Bereitstellungen verfassen abgefragt werden müssen.</para>
        </param>
        <param name="timeout">
          <para>Definiert die maximale Zeitspanne, das System diesen Vorgang fortzusetzen lässt, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <summary>
          <para>Ruft der Status der verfassen Bereitstellungen erstellt, die in der Beschreibung der Abfrage angegebenen Filtern (sofern vorhanden) entsprechen.
            Wenn die Compose-Bereitstellungen nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , die die asynchrone Abfragevorgang darstellt.
            Der Wert von TResult-Parameter ist ein <see cref="T:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList" /> , die die Liste der darstellt verfassen Bereitstellungen, die die Filtern in berücksichtigen die <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" /> und Anpassung an die Seite.
            Wenn die abfragebeschreibung für die angegebene keine entsprechende enthält, die Bereitstellungen erstellen hat, wird eine Liste von Einträgen 0 Einträge zurückgegeben.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetComposeDeploymentStatusPagedListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt; GetComposeDeploymentStatusPagedListAsync (this System.Fabric.FabricClient.QueryClient client, Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription composeDeploymentQueryDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt; GetComposeDeploymentStatusPagedListAsync(class System.Fabric.FabricClient/QueryClient client, class Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription composeDeploymentQueryDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.GetComposeDeploymentStatusPagedListAsync(System.Fabric.FabricClient.QueryClient,Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetComposeDeploymentStatusPagedListAsync : System.Fabric.FabricClient.QueryClient * Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt;" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.GetComposeDeploymentStatusPagedListAsync (client, composeDeploymentQueryDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+QueryClient" RefType="this" />
        <Parameter Name="composeDeploymentQueryDescription" Type="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="client">
          <see cref="T:System.Fabric.FabricClient" />-Objekt</param>
        <param name="composeDeploymentQueryDescription">
          <para>Die <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" /> , bestimmt die Bereitstellungen verfassen abgefragt werden müssen.</para>
        </param>
        <param name="timeout">
          <para>Definiert die maximale Zeitspanne, das System diesen Vorgang fortzusetzen lässt, vor der Rückgabe <see cref="T:System.TimeoutException" />.</para>
        </param>
        <param name="cancellationToken">
          <para>Das CancellationToken, das beobachten von der Vorgang. Es kann verwendet werden, um die Benachrichtigung verteilt wird, dass der Vorgang abgebrochen werden soll.</para>
        </param>
        <summary>
          <para>Ruft der Status der verfassen Bereitstellungen erstellt, die in der Beschreibung der Abfrage angegebenen Filtern (sofern vorhanden) entsprechen.
            Wenn die Compose-Bereitstellungen nicht auf eine Seite passen, wird eine Seite mit Ergebnissen sowie ein Fortsetzungstoken zurückgegeben, die zum Abrufen der nächsten Seite verwendet werden können.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , die die asynchrone Abfragevorgang darstellt.
            Der Wert von TResult-Parameter ist ein <see cref="T:Microsoft.ServiceFabric.Preview.Client.Query.ComposeDeploymentStatusList" /> , die die Liste der darstellt verfassen Bereitstellungen, die die Filtern in berücksichtigen die <see cref="T:Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentStatusQueryDescription" /> und Anpassung an die Seite.
            Wenn die abfragebeschreibung für die angegebene keine entsprechende enthält, die Bereitstellungen erstellen hat, wird eine Liste von Einträgen 0 Einträge zurückgegeben.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>
                Finden Sie unter <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für die Behandlung von allgemeinen FabricClient-Fehlern.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricException">
          <para>
                Siehe auch <see href="https://azure.microsoft.com/documentation/articles/service-fabric-errors-and-exceptions/" /> für allgemeine FabricClient Fehlerbehandlung.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="GetComposeDeploymentUpgradeProgressAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Fabric.ComposeDeploymentUpgradeProgress&gt; GetComposeDeploymentUpgradeProgressAsync (this System.Fabric.FabricClient.ComposeDeploymentClient client, string deploymentName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Fabric.ComposeDeploymentUpgradeProgress&gt; GetComposeDeploymentUpgradeProgressAsync(class System.Fabric.FabricClient/ComposeDeploymentClient client, string deploymentName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.GetComposeDeploymentUpgradeProgressAsync(System.Fabric.FabricClient.ComposeDeploymentClient,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetComposeDeploymentUpgradeProgressAsync (client As FabricClient.ComposeDeploymentClient, deploymentName As String) As Task(Of ComposeDeploymentUpgradeProgress)" />
      <MemberSignature Language="F#" Value="static member GetComposeDeploymentUpgradeProgressAsync : System.Fabric.FabricClient.ComposeDeploymentClient * string -&gt; System.Threading.Tasks.Task&lt;System.Fabric.ComposeDeploymentUpgradeProgress&gt;" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.GetComposeDeploymentUpgradeProgressAsync (client, deploymentName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Fabric.ComposeDeploymentUpgradeProgress&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+ComposeDeploymentClient" RefType="this" />
        <Parameter Name="deploymentName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="client">
          <see cref="T:System.Fabric.FabricClient" />-Objekt</param>
        <param name="deploymentName">
          <para>Der Name der Bereitstellung</para>
        </param>
        <summary>
          <para>Ruft ab, das Upgrade Status der angegebenen Bereitstellung zu erstellen.</para>
        </summary>
        <returns>
          <para>Ein <see cref="T:System.Threading.Tasks.Task" /> , dessen Ergebnis entspricht der upgradeverlauf des angegebenen Bereitstellung zu erstellen.</para>
        </returns>
        <remarks>To be added.</remarks>
        <exception cref="T:System.Fabric.FabricObjectClosedException">
          <para>Die <see cref="T:System.Fabric.FabricClient" /> Objekt befindet sich im Zustand "geschlossen". Löschen Sie die <see cref="T:System.Fabric.FabricClient" /> verwenden und instanziieren Sie ein neues Objekt <see cref="T:System.Fabric.FabricClient" /> Objekt.</para>
        </exception>
        <exception cref="T:System.Fabric.FabricElementNotFoundException">
          <para>
            <see cref="F:System.Fabric.FabricErrorCode.ComposeDeploymentNotFound" />: Die Compose-Bereitstellung ist nicht vorhanden.
            </para>
        </exception>
        <exception cref="T:System.TimeoutException">
          <para>Die Anforderung ein Timeout, aber möglicherweise wurden bereits akzeptiert wurde für die Verarbeitung vom System.</para>
        </exception>
        <exception cref="T:System.OperationCanceledException">
          <para>Die Anforderung wurde abgebrochen, bevor das Timeout abgelaufen ist, aber möglicherweise bereits wurde für die Verarbeitung vom System akzeptiert wurden.</para>
        </exception>
      </Docs>
    </Member>
    <Member MemberName="UpgradeComposeDeploymentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UpgradeComposeDeploymentAsync (this System.Fabric.FabricClient.ComposeDeploymentClient client, Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription upgradeDescription);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UpgradeComposeDeploymentAsync(class System.Fabric.FabricClient/ComposeDeploymentClient client, class Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription upgradeDescription) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.UpgradeComposeDeploymentAsync(System.Fabric.FabricClient.ComposeDeploymentClient,Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function UpgradeComposeDeploymentAsync (client As FabricClient.ComposeDeploymentClient, upgradeDescription As ComposeDeploymentUpgradeDescription) As Task" />
      <MemberSignature Language="F#" Value="static member UpgradeComposeDeploymentAsync : System.Fabric.FabricClient.ComposeDeploymentClient * Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription -&gt; System.Threading.Tasks.Task" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.UpgradeComposeDeploymentAsync (client, upgradeDescription)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+ComposeDeploymentClient" RefType="this" />
        <Parameter Name="upgradeDescription" Type="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription" />
      </Parameters>
      <Docs>
        <param name="client">To be added.</param>
        <param name="upgradeDescription">To be added.</param>
        <summary>
          <para>Startet das Upgrade für das Verfassen Bereitstellung durch den Namen der Bereitstellung im Cluster identifiziert.</para>
        </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeComposeDeploymentAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task UpgradeComposeDeploymentAsync (this System.Fabric.FabricClient.ComposeDeploymentClient client, Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription upgradeDescription, TimeSpan timeout, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task UpgradeComposeDeploymentAsync(class System.Fabric.FabricClient/ComposeDeploymentClient client, class Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription upgradeDescription, valuetype System.TimeSpan timeout, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Preview.Client.Extensions.UpgradeComposeDeploymentAsync(System.Fabric.FabricClient.ComposeDeploymentClient,Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription,System.TimeSpan,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpgradeComposeDeploymentAsync : System.Fabric.FabricClient.ComposeDeploymentClient * Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription * TimeSpan * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.ServiceFabric.Preview.Client.Extensions.UpgradeComposeDeploymentAsync (client, upgradeDescription, timeout, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Preview</AssemblyName>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="client" Type="System.Fabric.FabricClient+ComposeDeploymentClient" RefType="this" />
        <Parameter Name="upgradeDescription" Type="Microsoft.ServiceFabric.Preview.Client.Description.ComposeDeploymentUpgradeDescription" />
        <Parameter Name="timeout" Type="System.TimeSpan" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="client">To be added.</param>
        <param name="upgradeDescription">To be added.</param>
        <param name="timeout">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>
          <para>Startet das Upgrade für das Verfassen Bereitstellung durch den Namen der Bereitstellung im Cluster identifiziert.</para>
        </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>