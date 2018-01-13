<Type Name="MigrationOperationsExtensions" FullName="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class MigrationOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit MigrationOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module MigrationOperationsExtensions" />
  <TypeSignature Language="F#" Value="type MigrationOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Dies ist eine RESTFul-API, um Sie StorSimple-Objekte zu verwalten
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginUpdateDataContainerMigrationStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginUpdateDataContainerMigrationStatus (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginUpdateDataContainerMigrationStatus(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.BeginUpdateDataContainerMigrationStatus(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateDataContainerMigrationStatus : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.BeginUpdateDataContainerMigrationStatus (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.
            </param>
        <param name="configId">
            Erforderlich. Eindeutiger Bezeichner für die Konfiguration, die beim Importieren der Konfigurationsdatei an Dienst angegeben
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
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
    <Member MemberName="BeginUpdateDataContainerMigrationStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdateDataContainerMigrationStatusAsync (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdateDataContainerMigrationStatusAsync(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.BeginUpdateDataContainerMigrationStatusAsync(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateDataContainerMigrationStatusAsync : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.BeginUpdateDataContainerMigrationStatusAsync (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.
            </param>
        <param name="configId">
            Erforderlich. Eindeutiger Bezeichner für die Konfiguration, die beim Importieren der Konfigurationsdatei an Dienst angegeben
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
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
    <Member MemberName="BeginUpdateMigrationConfirmStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginUpdateMigrationConfirmStatus (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginUpdateMigrationConfirmStatus(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.BeginUpdateMigrationConfirmStatus(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateMigrationConfirmStatus : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.BeginUpdateMigrationConfirmStatus (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.
            </param>
        <param name="configId">
            Erforderlich. Eindeutiger Bezeichner für die Konfiguration, die beim Importieren der Konfigurationsdatei an Dienst angegeben
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
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
    <Member MemberName="BeginUpdateMigrationConfirmStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdateMigrationConfirmStatusAsync (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdateMigrationConfirmStatusAsync(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.BeginUpdateMigrationConfirmStatusAsync(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateMigrationConfirmStatusAsync : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.BeginUpdateMigrationConfirmStatusAsync (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.
            </param>
        <param name="configId">
            Erforderlich. Eindeutiger Bezeichner für die Konfiguration, die beim Importieren der Konfigurationsdatei an Dienst angegeben
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
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
    <Member MemberName="BeginUpdateMigrationPlan">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginUpdateMigrationPlan (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse BeginUpdateMigrationPlan(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.BeginUpdateMigrationPlan(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateMigrationPlan : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.BeginUpdateMigrationPlan (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.
            </param>
        <param name="configId">
            Erforderlich. Eindeutiger Bezeichner für die Konfiguration, die beim Importieren der Konfigurationsdatei an Dienst angegeben
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
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
    <Member MemberName="BeginUpdateMigrationPlanAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdateMigrationPlanAsync (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt; BeginUpdateMigrationPlanAsync(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.BeginUpdateMigrationPlanAsync(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateMigrationPlanAsync : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.BeginUpdateMigrationPlanAsync (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.
            </param>
        <param name="configId">
            Erforderlich. Eindeutiger Bezeichner für die Konfiguration, die beim Importieren der Konfigurationsdatei an Dienst angegeben
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
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
    <Member MemberName="ConfirmMigration">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus ConfirmMigration (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest confirmMigrationRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus ConfirmMigration(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest confirmMigrationRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.ConfirmMigration(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ConfirmMigration : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.ConfirmMigration (operations, configId, confirmMigrationRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="confirmMigrationRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.
            </param>
        <param name="configId">
            Erforderlich. Eindeutiger Bezeichner für die Konfiguration, die beim Importieren der Konfigurationsdatei an Dienst angegeben
            </param>
        <param name="confirmMigrationRequest">
            Erforderlich. Die Confirm-migrationsanforderung gibt die Liste der volumecontainer und die Zurücksetzung/der Commit-Vorgang ausgeführt werden
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
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
    <Member MemberName="ConfirmMigrationAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt; ConfirmMigrationAsync (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest confirmMigrationRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt; ConfirmMigrationAsync(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest confirmMigrationRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.ConfirmMigrationAsync(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ConfirmMigrationAsync : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.ConfirmMigrationAsync (operations, configId, confirmMigrationRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="confirmMigrationRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatusRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.
            </param>
        <param name="configId">
            Erforderlich. Eindeutiger Bezeichner für die Konfiguration, die beim Importieren der Konfigurationsdatei an Dienst angegeben
            </param>
        <param name="confirmMigrationRequest">
            Erforderlich. Die Confirm-migrationsanforderung gibt die Liste der volumecontainer und die Zurücksetzung/der Commit-Vorgang ausgeführt werden
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
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
    <Member MemberName="GetAllMigrationPlan">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList GetAllMigrationPlan (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList GetAllMigrationPlan(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetAllMigrationPlan(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetAllMigrationPlan : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetAllMigrationPlan (operations, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
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
    <Member MemberName="GetAllMigrationPlanAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt; GetAllMigrationPlanAsync (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt; GetAllMigrationPlanAsync(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetAllMigrationPlanAsync(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetAllMigrationPlanAsync : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetAllMigrationPlanAsync (operations, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
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
    <Member MemberName="GetDataContainerMigrationStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatusList GetDataContainerMigrationStatus (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatusList GetDataContainerMigrationStatus(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetDataContainerMigrationStatus(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetDataContainerMigrationStatus : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatusList" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetDataContainerMigrationStatus (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatusList</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.
            </param>
        <param name="configId">
            Erforderlich. Eindeutiger Bezeichner für die Konfiguration, die beim Importieren der Konfigurationsdatei an Dienst angegeben
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
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
    <Member MemberName="GetDataContainerMigrationStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatusList&gt; GetDataContainerMigrationStatusAsync (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatusList&gt; GetDataContainerMigrationStatusAsync(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetDataContainerMigrationStatusAsync(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetDataContainerMigrationStatusAsync : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatusList&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetDataContainerMigrationStatusAsync (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationDataContainerStatusList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.
            </param>
        <param name="configId">
            Erforderlich. Eindeutiger Bezeichner für die Konfiguration, die beim Importieren der Konfigurationsdatei an Dienst angegeben
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
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
    <Member MemberName="GetMigrationConfirmStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus GetMigrationConfirmStatus (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus GetMigrationConfirmStatus(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetMigrationConfirmStatus(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetMigrationConfirmStatus : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetMigrationConfirmStatus (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.
            </param>
        <param name="configId">
            Erforderlich. Eindeutiger Bezeichner für die Konfiguration, die beim Importieren der Konfigurationsdatei an Dienst angegeben
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
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
    <Member MemberName="GetMigrationConfirmStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus&gt; GetMigrationConfirmStatusAsync (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus&gt; GetMigrationConfirmStatusAsync(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetMigrationConfirmStatusAsync(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetMigrationConfirmStatusAsync : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetMigrationConfirmStatusAsync (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationConfirmStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.
            </param>
        <param name="configId">
            Erforderlich. Eindeutiger Bezeichner für die Konfiguration, die beim Importieren der Konfigurationsdatei an Dienst angegeben
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
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
    <Member MemberName="GetMigrationPlan">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList GetMigrationPlan (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList GetMigrationPlan(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetMigrationPlan(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetMigrationPlan : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetMigrationPlan (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.
            </param>
        <param name="configId">
            Erforderlich. Eindeutiger Bezeichner für die Konfiguration, die beim Importieren der Konfigurationsdatei an Dienst angegeben
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
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
    <Member MemberName="GetMigrationPlanAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt; GetMigrationPlanAsync (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt; GetMigrationPlanAsync(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetMigrationPlanAsync(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member GetMigrationPlanAsync : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.GetMigrationPlanAsync (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanList&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.
            </param>
        <param name="configId">
            Erforderlich. Eindeutiger Bezeichner für die Konfiguration, die beim Importieren der Konfigurationsdatei an Dienst angegeben
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
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
    <Member MemberName="ImportLegacyApplianceConfig">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.AzureOperationResponse ImportLegacyApplianceConfig (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig request, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.AzureOperationResponse ImportLegacyApplianceConfig(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig request, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.ImportLegacyApplianceConfig(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ImportLegacyApplianceConfig : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.Azure.AzureOperationResponse" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.ImportLegacyApplianceConfig (operations, configId, request, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.AzureOperationResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="request" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.
            </param>
        <param name="configId">
            Erforderlich. Eindeutige Id für die Konfiguration, die zu importierenden
            </param>
        <param name="request">
            Erforderlich. Legacy-Appliance Config importiert werden sollen
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
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
    <Member MemberName="ImportLegacyApplianceConfigAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt; ImportLegacyApplianceConfigAsync (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig request, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.AzureOperationResponse&gt; ImportLegacyApplianceConfigAsync(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig request, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.ImportLegacyApplianceConfigAsync(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member ImportLegacyApplianceConfigAsync : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.ImportLegacyApplianceConfigAsync (operations, configId, request, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.AzureOperationResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="request" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.LegacyApplianceConfig" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.
            </param>
        <param name="configId">
            Erforderlich. Eindeutige Id für die Konfiguration, die zu importierenden
            </param>
        <param name="request">
            Erforderlich. Legacy-Appliance Config importiert werden sollen
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
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
    <Member MemberName="MigrationImportDataContainer">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus MigrationImportDataContainer (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationImportDataContainerRequest importDCRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus MigrationImportDataContainer(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationImportDataContainerRequest importDCRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.MigrationImportDataContainer(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationImportDataContainerRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member MigrationImportDataContainer : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationImportDataContainerRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.MigrationImportDataContainer (operations, configId, importDCRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="importDCRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationImportDataContainerRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.
            </param>
        <param name="configId">
            Erforderlich. Eindeutiger Bezeichner für die Konfiguration, die beim Importieren der Konfigurationsdatei an Dienst angegeben
            </param>
        <param name="importDCRequest">
            Erforderlich. Importieren von Daten Container Anforderung gibt die Liste der Datencontainer für die Migration an
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
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
    <Member MemberName="MigrationImportDataContainerAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt; MigrationImportDataContainerAsync (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationImportDataContainerRequest importDCRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt; MigrationImportDataContainerAsync(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationImportDataContainerRequest importDCRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.MigrationImportDataContainerAsync(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationImportDataContainerRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member MigrationImportDataContainerAsync : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationImportDataContainerRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.MigrationImportDataContainerAsync (operations, configId, importDCRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="importDCRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationImportDataContainerRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.
            </param>
        <param name="configId">
            Erforderlich. Eindeutiger Bezeichner für die Konfiguration, die beim Importieren der Konfigurationsdatei an Dienst angegeben
            </param>
        <param name="importDCRequest">
            Erforderlich. Importieren von Daten Container Anforderung gibt die Liste der Datencontainer für die Migration an
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
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
    <Member MemberName="StartMigrationPlan">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus StartMigrationPlan (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest startPlanRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus StartMigrationPlan(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest startPlanRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.StartMigrationPlan(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member StartMigrationPlan : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.StartMigrationPlan (operations, startPlanRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="startPlanRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.
            </param>
        <param name="startPlanRequest">
            Erforderlich. Starten Sie die Migration Plan Request-Modell. Das Objekt übergibt die Liste der Volume-Container, deren Migration ETA berechnet werden muss
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
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
    <Member MemberName="StartMigrationPlanAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt; StartMigrationPlanAsync (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest startPlanRequest, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt; StartMigrationPlanAsync(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, class Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest startPlanRequest, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.StartMigrationPlanAsync(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member StartMigrationPlanAsync : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.StartMigrationPlanAsync (operations, startPlanRequest, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationJobStatus&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="startPlanRequest" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.MigrationPlanStartRequest" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.
            </param>
        <param name="startPlanRequest">
            Erforderlich. Starten Sie die Migration Plan Request-Modell. Das Objekt übergibt die Liste der Volume-Container, deren Migration ETA berechnet werden muss
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
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
    <Member MemberName="UpdateDataContainerMigrationStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo UpdateDataContainerMigrationStatus (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo UpdateDataContainerMigrationStatus(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.UpdateDataContainerMigrationStatus(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateDataContainerMigrationStatus : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.UpdateDataContainerMigrationStatus (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.
            </param>
        <param name="configId">
            Erforderlich. configId
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <summary>To be added.</summary>
        <returns>
            Informationen über die asynchrone Aufgabe
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateDataContainerMigrationStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateDataContainerMigrationStatusAsync (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateDataContainerMigrationStatusAsync(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.UpdateDataContainerMigrationStatusAsync(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateDataContainerMigrationStatusAsync : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.UpdateDataContainerMigrationStatusAsync (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.
            </param>
        <param name="configId">
            Erforderlich. configId
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <summary>To be added.</summary>
        <returns>
            Informationen über die asynchrone Aufgabe
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMigrationConfirmStatus">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo UpdateMigrationConfirmStatus (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo UpdateMigrationConfirmStatus(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.UpdateMigrationConfirmStatus(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateMigrationConfirmStatus : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.UpdateMigrationConfirmStatus (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.
            </param>
        <param name="configId">
            Erforderlich. Legacy-Konfigurations-Id, bei denen Migrationsregeln bestätigen Status muss aktualisiert werden
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <summary>To be added.</summary>
        <returns>
            Informationen über die asynchrone Aufgabe
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMigrationConfirmStatusAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateMigrationConfirmStatusAsync (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateMigrationConfirmStatusAsync(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.UpdateMigrationConfirmStatusAsync(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateMigrationConfirmStatusAsync : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.UpdateMigrationConfirmStatusAsync (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.
            </param>
        <param name="configId">
            Erforderlich. Legacy-Konfigurations-Id, bei denen Migrationsregeln bestätigen Status muss aktualisiert werden
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <summary>To be added.</summary>
        <returns>
            Informationen über die asynchrone Aufgabe
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMigrationPlan">
      <MemberSignature Language="C#" Value="public static Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo UpdateMigrationPlan (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo UpdateMigrationPlan(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.UpdateMigrationPlan(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateMigrationPlan : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.UpdateMigrationPlan (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.
            </param>
        <param name="configId">
            Erforderlich. configId
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
            </param>
        <summary>To be added.</summary>
        <returns>
            Informationen über die asynchrone Aufgabe
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMigrationPlanAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateMigrationPlanAsync (this Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt; UpdateMigrationPlanAsync(class Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations operations, string configId, class Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders customRequestHeaders) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.UpdateMigrationPlanAsync(Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations,System.String,Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders)" />
      <MemberSignature Language="F#" Value="static member UpdateMigrationPlanAsync : Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations * string * Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;" Usage="Microsoft.WindowsAzure.Management.StorSimple.MigrationOperationsExtensions.UpdateMigrationPlanAsync (operations, configId, customRequestHeaders)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Management.StorSimple</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Management.StorSimple.Models.TaskStatusInfo&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations" RefType="this" />
        <Parameter Name="configId" Type="System.String" />
        <Parameter Name="customRequestHeaders" Type="Microsoft.WindowsAzure.Management.StorSimple.Models.CustomRequestHeaders" />
      </Parameters>
      <Docs>
        <param name="operations">
            Verweis auf die Microsoft.WindowsAzure.Management.StorSimple.IMigrationOperations.
            </param>
        <param name="configId">
            Erforderlich. configId
            </param>
        <param name="customRequestHeaders">
            Erforderlich. Die benutzerdefinierte Anforderungsheader Client verwenden muss.
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