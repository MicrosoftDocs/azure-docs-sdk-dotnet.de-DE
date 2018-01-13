<Type Name="IMigrationOperations" FullName="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations">
  <TypeSignature Language="C#" Value="public interface IMigrationOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IMigrationOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IMigrationOperations" />
  <TypeSignature Language="F#" Value="type IMigrationOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Migration von Legacy-Appliance
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginUpdateDataContainerMigrationStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdateDataContainerMigrationStatusAsync (string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdateDataContainerMigrationStatusAsync(string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.BeginUpdateDataContainerMigrationStatusAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateDataContainerMigrationStatusAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="iMigrationOperations.BeginUpdateDataContainerMigrationStatusAsync (configId, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="configId">
            Eindeutiger Bezeichner für die Konfiguration, die beim Importieren der Konfigurationsdatei an Dienst angegeben
            </param>
        <param name="customRequestHeaders">
            Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Hydra-Spezifikation für Update Daten Container StatusThe rest-API-Updates den Status der Volume-Container-Migration von Zielgerät, Dienst für alle volumecontainer auf dem angegebenen
            </summary>
        <returns>
            Dies ist der Aufgabenantwort für alle asynchrone Aufrufe
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateMigrationConfirmStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdateMigrationConfirmStatusAsync (string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdateMigrationConfirmStatusAsync(string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.BeginUpdateMigrationConfirmStatusAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateMigrationConfirmStatusAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="iMigrationOperations.BeginUpdateMigrationConfirmStatusAsync (configId, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="configId">
            Eindeutiger Bezeichner für die Konfiguration, die beim Importieren der Konfigurationsdatei an Dienst angegeben
            </param>
        <param name="customRequestHeaders">
            Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Hydra-Spezifikation für Update bestätigen Migration StatusThe rest-API-Updates den Bestätigungsstatus (Commit/Rollback) von Ziel-Appliance, Dienst für alle Datencontainer in der angegebenen Konfiguration
            </summary>
        <returns>
            Dies ist der Aufgabenantwort für alle asynchrone Aufrufe
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateMigrationPlanAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdateMigrationPlanAsync (string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdateMigrationPlanAsync(string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.BeginUpdateMigrationPlanAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member BeginUpdateMigrationPlanAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="iMigrationOperations.BeginUpdateMigrationPlanAsync (configId, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="configId">
            Eindeutiger Bezeichner für die Konfiguration, die beim Importieren der Konfigurationsdatei an Dienst angegeben
            </param>
        <param name="customRequestHeaders">
            Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Hydra Spec Update Migration Plan Rest ApiThe Rest api aktualisiert des Migrationsplans aus Zielgerät für alle volumecontainern in der angegebenen Konfigurationsdatei verarbeiten
            </summary>
        <returns>
            Dies ist der Aufgabenantwort für alle asynchrone Aufrufe
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConfirmMigrationAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt; ConfirmMigrationAsync (string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest confirmMigrationRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt; ConfirmMigrationAsync(string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest confirmMigrationRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.ConfirmMigrationAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ConfirmMigrationAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt;" Usage="iMigrationOperations.ConfirmMigrationAsync (configId, confirmMigrationRequest, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="confirmMigrationRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="configId">
            Eindeutiger Bezeichner für die Konfiguration, die beim Importieren der Konfigurationsdatei an Dienst angegeben
            </param>
        <param name="confirmMigrationRequest">
            Die Confirm-migrationsanforderung gibt die Liste der volumecontainer und die Zurücksetzung/der Commit-Vorgang ausgeführt werden
            </param>
        <param name="customRequestHeaders">
            Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Bestätigen Sie Hydra-Spezifikation für die Migration Rest ApiThe Rest api bestätigt wird, die Commit- oder Rollback für die migrierten Datencontainer für alle Datencontainer in der angegebenen Konfiguration
            </summary>
        <returns>
            Das Antwort-Modell für die Migration des Auftragsstatus.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAllMigrationPlanAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt; GetAllMigrationPlanAsync (Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt; GetAllMigrationPlanAsync(class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.GetAllMigrationPlanAsync(Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAllMigrationPlanAsync : Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt;" Usage="iMigrationOperations.GetAllMigrationPlanAsync (customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customRequestHeaders">
            Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Hydra-Spezifikation für erhalten alle Migration Rest ApiThe Rest api die Config-Ids für alle Konfigurationen importiert, die für die ausgewählte Storsimple Ressource zurückgegebene
            </summary>
        <returns>
            Der Antworttext Migrationsplan Get rest-api.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDataContainerMigrationStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatusList&gt; GetDataContainerMigrationStatusAsync (string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatusList&gt; GetDataContainerMigrationStatusAsync(string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.GetDataContainerMigrationStatusAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetDataContainerMigrationStatusAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatusList&gt;" Usage="iMigrationOperations.GetDataContainerMigrationStatusAsync (configId, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="configId">
            Eindeutiger Bezeichner für die Konfiguration, die beim Importieren der Konfigurationsdatei an Dienst angegeben
            </param>
        <param name="customRequestHeaders">
            Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Hydra-Spezifikation für Get Data Container Migration StatusThe rest api gibt den Status der Volume-Container Migrationsstatus vom Dienst für alle volumecontainer auf dem angegebenen
            </summary>
        <returns>
            Der Antworttext für Daten Container Migrationsstatus abgerufen werden.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMigrationConfirmStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus&gt; GetMigrationConfirmStatusAsync (string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus&gt; GetMigrationConfirmStatusAsync(string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.GetMigrationConfirmStatusAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetMigrationConfirmStatusAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus&gt;" Usage="iMigrationOperations.GetMigrationConfirmStatusAsync (configId, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="configId">
            Eindeutiger Bezeichner für die Konfiguration, die beim Importieren der Konfigurationsdatei an Dienst angegeben
            </param>
        <param name="customRequestHeaders">
            Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Hydra-Spezifikation für Get bestätigen Migration Status Rest ApiThe rest api ruft der Bestätigungsstatus (Commit/Rollback), vom Dienst für alle volumecontainer auf dem angegebenen
            </summary>
        <returns>
            Der Antworttext der Migration den Status bestätigen rest-api.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetMigrationPlanAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt; GetMigrationPlanAsync (string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt; GetMigrationPlanAsync(string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.GetMigrationPlanAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetMigrationPlanAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt;" Usage="iMigrationOperations.GetMigrationPlanAsync (configId, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="configId">
            Eindeutiger Bezeichner für die Konfiguration, die beim Importieren der Konfigurationsdatei an Dienst angegeben
            </param>
        <param name="customRequestHeaders">
            Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Hydra-Spezifikation für die Migration PlanThe Get rest-api abrufen, die vom Dienst für alle volumecontainern in der angegebenen Konfigurationsdatei Planen der migration
            </summary>
        <returns>
            Der Antworttext Migrationsplan Get rest-api.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ImportLegacyApplianceConfigAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; ImportLegacyApplianceConfigAsync (string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig request, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; ImportLegacyApplianceConfigAsync(string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig request, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.ImportLegacyApplianceConfigAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ImportLegacyApplianceConfigAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="iMigrationOperations.ImportLegacyApplianceConfigAsync (configId, request, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="request" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="configId">
            Eindeutige Id für die Konfiguration, die zu importierenden
            </param>
        <param name="request">
            Legacy-Appliance Config importiert werden sollen
            </param>
        <param name="customRequestHeaders">
            Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Hydra-Spezifikation für Import älterer Appliance Config rest-api. Die Rest-API-importiert die ältere Konfiguration an den Dienst
            </summary>
        <returns>
            Eine standarddienstantwort einschließlich ein HTTP-Statuscodes und einer Anforderungs-ID.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MigrationImportDataContainerAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt; MigrationImportDataContainerAsync (string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationImportDataContainerRequest importDCRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt; MigrationImportDataContainerAsync(string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationImportDataContainerRequest importDCRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.MigrationImportDataContainerAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationImportDataContainerRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member MigrationImportDataContainerAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationImportDataContainerRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt;" Usage="iMigrationOperations.MigrationImportDataContainerAsync (configId, importDCRequest, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="importDCRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationImportDataContainerRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="configId">
            Eindeutiger Bezeichner für die Konfiguration, die beim Importieren der Konfigurationsdatei an Dienst angegeben
            </param>
        <param name="importDCRequest">
            Importieren von Daten Container Anforderung gibt die Liste der Datencontainer für die Migration an
            </param>
        <param name="customRequestHeaders">
            Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Hydra-Spezifikation für Import Daten Container Rest ApiThe rest api initiiert die Migration der volumecontainer für alle Daten/Container in der angegebenen Konfiguration
            </summary>
        <returns>
            Das Antwort-Modell für die Migration des Auftragsstatus.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartMigrationPlanAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt; StartMigrationPlanAsync (Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest startPlanRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt; StartMigrationPlanAsync(class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest startPlanRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.StartMigrationPlanAsync(Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StartMigrationPlanAsync : Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt;" Usage="iMigrationOperations.StartMigrationPlanAsync (startPlanRequest, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="startPlanRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="startPlanRequest">
            Starten Sie die Migration Plan Request-Modell. Das Objekt übergibt die Liste der Volume-Container, deren Migration ETA berechnet werden muss
            </param>
        <param name="customRequestHeaders">
            Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>
            Hydra Spezifikation Start Migrationsplan rest APIThe Rest-api der Schätzung der Zeit, bis die Migration für alle/spezifische volumecontainern in der angegebenen Konfiguration gestartet wird.
            </summary>
        <returns>
            Das Antwort-Modell für die Migration des Auftragsstatus.
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDataContainerMigrationStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateDataContainerMigrationStatusAsync (string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateDataContainerMigrationStatusAsync(string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.UpdateDataContainerMigrationStatusAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateDataContainerMigrationStatusAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="iMigrationOperations.UpdateDataContainerMigrationStatusAsync (configId, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="configId">
            configId
            </param>
        <param name="customRequestHeaders">
            Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>To be added.</summary>
        <returns>
            Informationen über die asynchrone Aufgabe
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMigrationConfirmStatusAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateMigrationConfirmStatusAsync (string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateMigrationConfirmStatusAsync(string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.UpdateMigrationConfirmStatusAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateMigrationConfirmStatusAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="iMigrationOperations.UpdateMigrationConfirmStatusAsync (configId, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="configId">
            Legacy-Konfigurations-Id, bei denen Migrationsregeln bestätigen Status muss aktualisiert werden
            </param>
        <param name="customRequestHeaders">
            Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>To be added.</summary>
        <returns>
            Informationen über die asynchrone Aufgabe
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMigrationPlanAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateMigrationPlanAsync (string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateMigrationPlanAsync(string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.UpdateMigrationPlanAsync(System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member UpdateMigrationPlanAsync : string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="iMigrationOperations.UpdateMigrationPlanAsync (configId, customRequestHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="configId">
            configId
            </param>
        <param name="customRequestHeaders">
            Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <param name="cancellationToken">
            Abbruchtoken.
            </param>
        <summary>To be added.</summary>
        <returns>
            Informationen über die asynchrone Aufgabe
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>