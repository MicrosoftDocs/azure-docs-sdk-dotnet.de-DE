<Type Name="JobScheduleOperationsExtensions" FullName="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class JobScheduleOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit JobScheduleOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module JobScheduleOperationsExtensions" />
  <TypeSignature Language="F#" Value="type JobScheduleOperationsExtensions = class" />
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
            Erweiterungsmethoden für JobScheduleOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Add">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddHeaders Add (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter cloudJobSchedule, Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddOptions jobScheduleAddOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddHeaders Add(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter cloudJobSchedule, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddOptions jobScheduleAddOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Add(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter,Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddOptions)" />
      <MemberSignature Language="F#" Value="static member Add : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter * Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Add (operations, cloudJobSchedule, jobScheduleAddOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="cloudJobSchedule" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter" />
        <Parameter Name="jobScheduleAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="cloudJobSchedule">
            Der Auftragszeitplan hinzugefügt werden.
            </param>
        <param name="jobScheduleAddOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Das angegebene Konto hinzugefügt Zeitplan für einen Auftrag.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AddAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddHeaders&gt; AddAsync (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter cloudJobSchedule, Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddOptions jobScheduleAddOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddHeaders&gt; AddAsync(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter cloudJobSchedule, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddOptions jobScheduleAddOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.AddAsync(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter,Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member AddAsync : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter * Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.AddAsync (operations, cloudJobSchedule, jobScheduleAddOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions/&lt;AddAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="cloudJobSchedule" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddParameter" />
        <Parameter Name="jobScheduleAddOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleAddOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="cloudJobSchedule">
            Der Auftragszeitplan hinzugefügt werden.
            </param>
        <param name="jobScheduleAddOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Das angegebene Konto hinzugefügt Zeitplan für einen Auftrag.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteHeaders Delete (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteOptions jobScheduleDeleteOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteHeaders Delete(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteOptions jobScheduleDeleteOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Delete(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteOptions)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Delete (operations, jobScheduleId, jobScheduleDeleteOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobScheduleId">
            Die ID des Auftragszeitplans zu löschen.
            </param>
        <param name="jobScheduleDeleteOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Löscht einen Zeitplan für Aufträge aus dem angegebenen Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn Sie einen Auftragszeitplan löschen, löscht diese auch alle Aufträge und Aufgaben unter diesen Zeitplan an. Wenn Aufgaben gelöscht werden, werden auch alle Dateien in ihren Arbeitsverzeichnissen auf den Serverknoten gelöscht (während der Beibehaltungsdauer wird ignoriert). Die Auftrag-Zeitplan-Statistiken sind nicht mehr zugegriffen werden kann, sobald der Auftragszeitplan gelöscht wurde, obwohl sie weiterhin zum Konto lebensdauerstatistiken hinzugezählt werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteHeaders&gt; DeleteAsync (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteOptions jobScheduleDeleteOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteHeaders&gt; DeleteAsync(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteOptions jobScheduleDeleteOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.DeleteAsync(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.DeleteAsync (operations, jobScheduleId, jobScheduleDeleteOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions/&lt;DeleteAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleDeleteOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleDeleteOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobScheduleId">
            Die ID des Auftragszeitplans zu löschen.
            </param>
        <param name="jobScheduleDeleteOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Löscht einen Zeitplan für Aufträge aus dem angegebenen Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Wenn Sie einen Auftragszeitplan löschen, löscht diese auch alle Aufträge und Aufgaben unter diesen Zeitplan an. Wenn Aufgaben gelöscht werden, werden auch alle Dateien in ihren Arbeitsverzeichnissen auf den Serverknoten gelöscht (während der Beibehaltungsdauer wird ignoriert). Die Auftrag-Zeitplan-Statistiken sind nicht mehr zugegriffen werden kann, sobald der Auftragszeitplan gelöscht wurde, obwohl sie weiterhin zum Konto lebensdauerstatistiken hinzugezählt werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Disable">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableHeaders Disable (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableOptions jobScheduleDisableOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableHeaders Disable(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableOptions jobScheduleDisableOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Disable(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableOptions)" />
      <MemberSignature Language="F#" Value="static member Disable : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Disable (operations, jobScheduleId, jobScheduleDisableOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleDisableOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobScheduleId">
            Die ID des Auftragszeitplans zu deaktivieren.
            </param>
        <param name="jobScheduleDisableOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Deaktiviert einen Auftragszeitplan.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Keine neuen Aufträge werden erstellt werden, bis wieder der Auftragszeitplan aktiviert ist.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DisableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableHeaders&gt; DisableAsync (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableOptions jobScheduleDisableOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableHeaders&gt; DisableAsync(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableOptions jobScheduleDisableOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.DisableAsync(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DisableAsync : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.DisableAsync (operations, jobScheduleId, jobScheduleDisableOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions/&lt;DisableAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleDisableOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleDisableOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobScheduleId">
            Die ID des Auftragszeitplans zu deaktivieren.
            </param>
        <param name="jobScheduleDisableOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Deaktiviert einen Auftragszeitplan.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Keine neuen Aufträge werden erstellt werden, bis wieder der Auftragszeitplan aktiviert ist.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Enable">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableHeaders Enable (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableOptions jobScheduleEnableOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableHeaders Enable(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableOptions jobScheduleEnableOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Enable(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableOptions)" />
      <MemberSignature Language="F#" Value="static member Enable : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Enable (operations, jobScheduleId, jobScheduleEnableOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleEnableOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobScheduleId">
            Die ID des Auftragszeitplans zu aktivieren.
            </param>
        <param name="jobScheduleEnableOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Ermöglicht einen Auftragszeitplan.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnableAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableHeaders&gt; EnableAsync (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableOptions jobScheduleEnableOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableHeaders&gt; EnableAsync(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableOptions jobScheduleEnableOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.EnableAsync(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member EnableAsync : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.EnableAsync (operations, jobScheduleId, jobScheduleEnableOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions/&lt;EnableAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleEnableOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleEnableOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobScheduleId">
            Die ID des Auftragszeitplans zu aktivieren.
            </param>
        <param name="jobScheduleEnableOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ermöglicht einen Auftragszeitplan.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exists">
      <MemberSignature Language="C#" Value="public static bool Exists (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsOptions jobScheduleExistsOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig bool Exists(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsOptions jobScheduleExistsOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Exists(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsOptions)" />
      <MemberSignature Language="F#" Value="static member Exists : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsOptions -&gt; bool" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Exists (operations, jobScheduleId, jobScheduleExistsOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleExistsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobScheduleId">
            Die ID des Auftragszeitplans, die Sie überprüfen möchten.
            </param>
        <param name="jobScheduleExistsOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Überprüft, ob der angegebene Auftrag-Zeitplan vorhanden ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsOptions jobScheduleExistsOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsOptions jobScheduleExistsOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.ExistsAsync(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ExistsAsync : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.ExistsAsync (operations, jobScheduleId, jobScheduleExistsOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions/&lt;ExistsAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleExistsOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleExistsOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobScheduleId">
            Die ID des Auftragszeitplans, die Sie überprüfen möchten.
            </param>
        <param name="jobScheduleExistsOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Überprüft, ob der angegebene Auftrag-Zeitplan vorhanden ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule Get (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetOptions jobScheduleGetOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule Get(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetOptions jobScheduleGetOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Get(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetOptions)" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Get (operations, jobScheduleId, jobScheduleGetOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobScheduleId">
            Die ID des Auftragszeitplans zu erhalten.
            </param>
        <param name="jobScheduleGetOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Ruft Informationen über den angegebenen Auftrag-Zeitplan ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt; GetAsync (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetOptions jobScheduleGetOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt; GetAsync(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetOptions jobScheduleGetOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.GetAsync(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.GetAsync (operations, jobScheduleId, jobScheduleGetOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions/&lt;GetAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleGetOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleGetOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobScheduleId">
            Die ID des Auftragszeitplans zu erhalten.
            </param>
        <param name="jobScheduleGetOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft Informationen über den angegebenen Auftrag-Zeitplan ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt; List (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, Microsoft.Azure.Batch.Protocol.Models.JobScheduleListOptions jobScheduleListOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt; List(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleListOptions jobScheduleListOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.List(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,Microsoft.Azure.Batch.Protocol.Models.JobScheduleListOptions)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * Microsoft.Azure.Batch.Protocol.Models.JobScheduleListOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.List (operations, jobScheduleListOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleListOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobScheduleListOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Zeigt eine Liste aller Auftragszeitpläne im angegebenen Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;&gt; ListAsync (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, Microsoft.Azure.Batch.Protocol.Models.JobScheduleListOptions jobScheduleListOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;&gt; ListAsync(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleListOptions jobScheduleListOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.ListAsync(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,Microsoft.Azure.Batch.Protocol.Models.JobScheduleListOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * Microsoft.Azure.Batch.Protocol.Models.JobScheduleListOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.ListAsync (operations, jobScheduleListOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions/&lt;ListAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleListOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleListOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobScheduleListOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zeigt eine Liste aller Auftragszeitpläne im angegebenen Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt; ListNext (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions jobScheduleListNextOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt; ListNext(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions jobScheduleListNextOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.ListNext(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.ListNext (operations, nextPageLink, jobScheduleListNextOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobScheduleListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="jobScheduleListNextOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Zeigt eine Liste aller Auftragszeitpläne im angegebenen Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;&gt; ListNextAsync (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string nextPageLink, Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions jobScheduleListNextOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;&gt; ListNextAsync(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string nextPageLink, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions jobScheduleListNextOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.ListNextAsync(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.ListNextAsync (operations, nextPageLink, jobScheduleListNextOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions/&lt;ListNextAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Batch.Protocol.Models.CloudJobSchedule&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="jobScheduleListNextOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleListNextOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="jobScheduleListNextOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Zeigt eine Liste aller Auftragszeitpläne im angegebenen Konto.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Patch">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchHeaders Patch (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter jobSchedulePatchParameter, Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions jobSchedulePatchOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchHeaders Patch(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter jobSchedulePatchParameter, class Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions jobSchedulePatchOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Patch(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter,Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions)" />
      <MemberSignature Language="F#" Value="static member Patch : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter * Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Patch (operations, jobScheduleId, jobSchedulePatchParameter, jobSchedulePatchOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobSchedulePatchParameter" Type="Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter" />
        <Parameter Name="jobSchedulePatchOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobScheduleId">
            Die ID des Auftragszeitplans zu aktualisieren.
            </param>
        <param name="jobSchedulePatchParameter">
            Die Parameter für die Anforderung.
            </param>
        <param name="jobSchedulePatchOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Aktualisiert die Eigenschaften des Zeitplans angegebenen Auftrag.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Dies ersetzt nur die Eigenschaften des Auftragszeitplans in der Anforderung angegeben.
            Die Zeitplan-Eigenschaft nicht mit dieser Anforderung angegeben ist, wird der Batch-Dienst z. B. den Zeitplan des vorhandenen beibehalten. Änderungen an einem Auftrag planen nur Auswirkungen auf Aufträge im Zeitplan erstellt werden, nachdem das Update stattgefunden hat; derzeit ausgeführte Aufträge sind nicht betroffen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="PatchAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchHeaders&gt; PatchAsync (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter jobSchedulePatchParameter, Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions jobSchedulePatchOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchHeaders&gt; PatchAsync(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter jobSchedulePatchParameter, class Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions jobSchedulePatchOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.PatchAsync(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter,Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member PatchAsync : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter * Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.PatchAsync (operations, jobScheduleId, jobSchedulePatchParameter, jobSchedulePatchOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions/&lt;PatchAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobSchedulePatchParameter" Type="Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchParameter" />
        <Parameter Name="jobSchedulePatchOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobSchedulePatchOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobScheduleId">
            Die ID des Auftragszeitplans zu aktualisieren.
            </param>
        <param name="jobSchedulePatchParameter">
            Die Parameter für die Anforderung.
            </param>
        <param name="jobSchedulePatchOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert die Eigenschaften des Zeitplans angegebenen Auftrag.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Dies ersetzt nur die Eigenschaften des Auftragszeitplans in der Anforderung angegeben.
            Die Zeitplan-Eigenschaft nicht mit dieser Anforderung angegeben ist, wird der Batch-Dienst z. B. den Zeitplan des vorhandenen beibehalten. Änderungen an einem Auftrag planen nur Auswirkungen auf Aufträge im Zeitplan erstellt werden, nachdem das Update stattgefunden hat; derzeit ausgeführte Aufträge sind nicht betroffen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Terminate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateHeaders Terminate (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateOptions jobScheduleTerminateOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateHeaders Terminate(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateOptions jobScheduleTerminateOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Terminate(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateOptions)" />
      <MemberSignature Language="F#" Value="static member Terminate : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Terminate (operations, jobScheduleId, jobScheduleTerminateOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleTerminateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobScheduleId">
            Die ID der der Auftragszeitplan beendet wird.
            </param>
        <param name="jobScheduleTerminateOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Beendet einen Auftragszeitplan.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TerminateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateHeaders&gt; TerminateAsync (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateOptions jobScheduleTerminateOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateHeaders&gt; TerminateAsync(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateOptions jobScheduleTerminateOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.TerminateAsync(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member TerminateAsync : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.TerminateAsync (operations, jobScheduleId, jobScheduleTerminateOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions/&lt;TerminateAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleTerminateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleTerminateOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobScheduleId">
            Die ID der der Auftragszeitplan beendet wird.
            </param>
        <param name="jobScheduleTerminateOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Beendet einen Auftragszeitplan.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateHeaders Update (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter jobScheduleUpdateParameter, Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateOptions jobScheduleUpdateOptions = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateHeaders Update(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter jobScheduleUpdateParameter, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateOptions jobScheduleUpdateOptions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Update(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter,Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateOptions)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter * Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateOptions -&gt; Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateHeaders" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.Update (operations, jobScheduleId, jobScheduleUpdateParameter, jobScheduleUpdateOptions)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateHeaders</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleUpdateParameter" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter" />
        <Parameter Name="jobScheduleUpdateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateOptions" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobScheduleId">
            Die ID des Auftragszeitplans zu aktualisieren.
            </param>
        <param name="jobScheduleUpdateParameter">
            Die Parameter für die Anforderung.
            </param>
        <param name="jobScheduleUpdateOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <summary>
            Aktualisiert die Eigenschaften des Zeitplans angegebenen Auftrag.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Dadurch wird vollständig ersetzt alle aktualisierbaren Eigenschaften des Auftragszeitplans. Wenn der Zeitplan-Eigenschaft nicht mit dieser Anforderung angegeben ist, wird der Batch-Dienst z. B. den Zeitplan des vorhandenen entfernt. Änderungen an einem Auftrag planen nur Auswirkungen auf Aufträge im Zeitplan erstellt werden, nachdem das Update stattgefunden hat; derzeit ausgeführte Aufträge sind nicht betroffen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateHeaders&gt; UpdateAsync (this Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter jobScheduleUpdateParameter, Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateOptions jobScheduleUpdateOptions = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateHeaders&gt; UpdateAsync(class Microsoft.Azure.Batch.Protocol.IJobScheduleOperations operations, string jobScheduleId, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter jobScheduleUpdateParameter, class Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateOptions jobScheduleUpdateOptions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.UpdateAsync(Microsoft.Azure.Batch.Protocol.IJobScheduleOperations,System.String,Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter,Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Batch.Protocol.IJobScheduleOperations * string * Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter * Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateHeaders&gt;" Usage="Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions.UpdateAsync (operations, jobScheduleId, jobScheduleUpdateParameter, jobScheduleUpdateOptions, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.JobScheduleOperationsExtensions/&lt;UpdateAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateHeaders&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Batch.Protocol.IJobScheduleOperations" RefType="this" />
        <Parameter Name="jobScheduleId" Type="System.String" />
        <Parameter Name="jobScheduleUpdateParameter" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateParameter" />
        <Parameter Name="jobScheduleUpdateOptions" Type="Microsoft.Azure.Batch.Protocol.Models.JobScheduleUpdateOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="jobScheduleId">
            Die ID des Auftragszeitplans zu aktualisieren.
            </param>
        <param name="jobScheduleUpdateParameter">
            Die Parameter für die Anforderung.
            </param>
        <param name="jobScheduleUpdateOptions">
            Zusätzliche Parameter für den Vorgang
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Aktualisiert die Eigenschaften des Zeitplans angegebenen Auftrag.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Dadurch wird vollständig ersetzt alle aktualisierbaren Eigenschaften des Auftragszeitplans. Wenn der Zeitplan-Eigenschaft nicht mit dieser Anforderung angegeben ist, wird der Batch-Dienst z. B. den Zeitplan des vorhandenen entfernt. Änderungen an einem Auftrag planen nur Auswirkungen auf Aufträge im Zeitplan erstellt werden, nachdem das Update stattgefunden hat; derzeit ausgeführte Aufträge sind nicht betroffen.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>