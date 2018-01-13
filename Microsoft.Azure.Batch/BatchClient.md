<Type Name="BatchClient" FullName="Microsoft.Azure.Batch.BatchClient">
  <TypeSignature Language="C#" Value="public class BatchClient : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit BatchClient extends System.Object implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.BatchClient" />
  <TypeSignature Language="VB.NET" Value="Public Class BatchClient&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type BatchClient = class&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
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
            Der Client für eine Azure Batch-Konto verwendet, um den Batch-Dienst zuzugreifen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ApplicationOperations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ApplicationOperations ApplicationOperations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ApplicationOperations ApplicationOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchClient.ApplicationOperations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ApplicationOperations As ApplicationOperations" />
      <MemberSignature Language="F#" Value="member this.ApplicationOperations : Microsoft.Azure.Batch.ApplicationOperations" Usage="Microsoft.Azure.Batch.BatchClient.ApplicationOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ApplicationOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine <see cref="P:Microsoft.Azure.Batch.BatchClient.ApplicationOperations" /> für Operationen anwendungsbezogenen auf das zugeordnete Konto.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CertificateOperations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.CertificateOperations CertificateOperations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.CertificateOperations CertificateOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchClient.CertificateOperations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CertificateOperations As CertificateOperations" />
      <MemberSignature Language="F#" Value="member this.CertificateOperations : Microsoft.Azure.Batch.CertificateOperations" Usage="Microsoft.Azure.Batch.BatchClient.CertificateOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.CertificateOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine <see cref="P:Microsoft.Azure.Batch.BatchClient.CertificateOperations" /> für Operationen zertifikatbezogene auf das zugeordnete Konto.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Close">
      <MemberSignature Language="C#" Value="public void Close ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Close() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClient.Close" />
      <MemberSignature Language="VB.NET" Value="Public Sub Close ()" />
      <MemberSignature Language="F#" Value="member this.Close : unit -&gt; unit" Usage="batchClient.Close " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Schließt die aktuelle Instanz von <see cref="T:Microsoft.Azure.Batch.BatchClient" />.  
            Geschlossen von Instanzen von <see cref="T:Microsoft.Azure.Batch.BatchClient" /> können keine Aufrufe an den Batch-Dienst vorgenommen werden und das Verhalten und die Werte der anderen Methoden oder Eigenschaften sind nicht definiert. Diese Einschränkungen gelten auch sofort für alle Objekte, die zu diesem Instantation zurückverfolgen können <see cref="T:Microsoft.Azure.Batch.BatchClient" />.
            Diese Methode ist hinsichtlich und beliebig häufig aufgerufen werden kann.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloseAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task CloseAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task CloseAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClient.CloseAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function CloseAsync () As Task" />
      <MemberSignature Language="F#" Value="member this.CloseAsync : unit -&gt; System.Threading.Tasks.Task" Usage="batchClient.CloseAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Startet einen asynchronen Vorgang zum Schließen der aktuellen Instanz der <see cref="T:Microsoft.Azure.Batch.BatchClient" />.  
            Geschlossen von Instanzen von <see cref="T:Microsoft.Azure.Batch.BatchClient" /> können keine Aufrufe an den Batch-Dienst vorgenommen werden und das Verhalten und die Werte der anderen Methoden oder Eigenschaften sind nicht definiert. Diese Einschränkungen gelten auch sofort für alle Objekte, die zu diesem Instantation zurückverfolgen können <see cref="T:Microsoft.Azure.Batch.BatchClient" />.
            Diese Methode ist hinsichtlich und beliebig häufig aufgerufen werden kann.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomBehaviors">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Batch.BatchClientBehavior&gt; CustomBehaviors" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchClient.CustomBehaviors" />
      <MemberSignature Language="VB.NET" Value="Public Property CustomBehaviors As IList(Of BatchClientBehavior)" />
      <MemberSignature Language="F#" Value="member this.CustomBehaviors : System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt; with get, set" Usage="Microsoft.Azure.Batch.BatchClient.CustomBehaviors" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.Batch.BatchClientBehavior&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt eine Liste der Verhaltensweisen, die ändern oder Anpassen von Anforderungen an den Batch-Dienst.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>Diese Verhaltensweisen werden von untergeordneten Objekten geerbt.</para>
          <para>Änderungen werden in der Reihenfolge der Auflistung angewendet. Der letzte write Wins.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClient.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="batchClient.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Aufrufe <see cref="M:Microsoft.Azure.Batch.BatchClient.Close" /> und frei, die nicht verwalteten Ressourcen und optional auch die verwalteten Ressourcen von der <see cref="T:Microsoft.Azure.Batch.BatchClient" />.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected virtual void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClient.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="abstract member Dispose : bool -&gt; unit&#xA;override this.Dispose : bool -&gt; unit" Usage="batchClient.Dispose disposing" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing">Gibt an, ob das Objekt wird verworfen oder freigegeben.  Bei "true", wird das Objekt freigegeben wird, und verwaltete Ressource freigeben kann.  Wenn "false" wird das Objekt abgeschlossen wird, und sollten nur nicht verwaltete Ressourcen frei.</param>
        <summary>
            Vom nicht verwalteten Ressourcen frei der <see cref="T:Microsoft.Azure.Batch.BatchClient" />, und optional verwaltete Ressourcen frei.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobOperations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobOperations JobOperations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobOperations JobOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchClient.JobOperations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobOperations As JobOperations" />
      <MemberSignature Language="F#" Value="member this.JobOperations : Microsoft.Azure.Batch.JobOperations" Usage="Microsoft.Azure.Batch.BatchClient.JobOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine <see cref="P:Microsoft.Azure.Batch.BatchClient.JobOperations" /> für Operationen auftragsbezogene auf das zugeordnete Konto.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JobScheduleOperations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.JobScheduleOperations JobScheduleOperations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.JobScheduleOperations JobScheduleOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchClient.JobScheduleOperations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JobScheduleOperations As JobScheduleOperations" />
      <MemberSignature Language="F#" Value="member this.JobScheduleOperations : Microsoft.Azure.Batch.JobScheduleOperations" Usage="Microsoft.Azure.Batch.BatchClient.JobScheduleOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.JobScheduleOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine <see cref="P:Microsoft.Azure.Batch.BatchClient.JobScheduleOperations" /> zum Ausführen des Auftrags Zeitplan-bezogenen Vorgänge für das zugeordnete Konto.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Open">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.BatchClient Open (Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.BatchClient Open(class Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClient.Open(Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Open (credentials As BatchSharedKeyCredentials) As BatchClient" />
      <MemberSignature Language="F#" Value="static member Open : Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials -&gt; Microsoft.Azure.Batch.BatchClient" Usage="Microsoft.Azure.Batch.BatchClient.Open credentials" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.BatchClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials" />
      </Parameters>
      <Docs>
        <param name="credentials">Die Anmeldeinformationen für den Batch-Konto.</param>
        <summary>
            Erstellt eine Instanz von <see cref="T:Microsoft.Azure.Batch.BatchClient" />.
            </summary>
        <returns>Eine Instanz von <see cref="T:Microsoft.Azure.Batch.Protocol.BatchServiceClient" />.</returns>
        <remarks>
            Dies ist ein blockierender Aufruf. Für eine nicht blockierende entspricht, finden Sie unter<see cref="M:Microsoft.Azure.Batch.BatchClient.OpenAsync(Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials)" /></remarks>
      </Docs>
    </Member>
    <Member MemberName="Open">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.BatchClient Open (Microsoft.Azure.Batch.Auth.BatchTokenCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.BatchClient Open(class Microsoft.Azure.Batch.Auth.BatchTokenCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClient.Open(Microsoft.Azure.Batch.Auth.BatchTokenCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Open (credentials As BatchTokenCredentials) As BatchClient" />
      <MemberSignature Language="F#" Value="static member Open : Microsoft.Azure.Batch.Auth.BatchTokenCredentials -&gt; Microsoft.Azure.Batch.BatchClient" Usage="Microsoft.Azure.Batch.BatchClient.Open credentials" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.BatchClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.Batch.Auth.BatchTokenCredentials" />
      </Parameters>
      <Docs>
        <param name="credentials">Die Anmeldeinformationen für den Azure Active Directory-Batch-Konto.</param>
        <summary>
            Erstellt eine Instanz von <see cref="T:Microsoft.Azure.Batch.BatchClient" />.
            </summary>
        <returns>Eine Instanz von <see cref="T:Microsoft.Azure.Batch.Protocol.BatchServiceClient" />.</returns>
        <remarks>
            Dies ist ein blockierender Aufruf. Für eine nicht blockierende entspricht, finden Sie unter<see cref="M:Microsoft.Azure.Batch.BatchClient.OpenAsync(Microsoft.Azure.Batch.Auth.BatchTokenCredentials)" /></remarks>
      </Docs>
    </Member>
    <Member MemberName="Open">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Batch.BatchClient Open (Microsoft.Azure.Batch.Protocol.BatchServiceClient restClient);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Batch.BatchClient Open(class Microsoft.Azure.Batch.Protocol.BatchServiceClient restClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClient.Open(Microsoft.Azure.Batch.Protocol.BatchServiceClient)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function Open (restClient As BatchServiceClient) As BatchClient" />
      <MemberSignature Language="F#" Value="static member Open : Microsoft.Azure.Batch.Protocol.BatchServiceClient -&gt; Microsoft.Azure.Batch.BatchClient" Usage="Microsoft.Azure.Batch.BatchClient.Open restClient" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.BatchClient</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="restClient" Type="Microsoft.Azure.Batch.Protocol.BatchServiceClient" />
      </Parameters>
      <Docs>
        <param name="restClient">Die Instanz von <see cref="T:Microsoft.Azure.Batch.Protocol.BatchServiceClient" /> für alle Aufrufe an die Batch-Dienst verwendet. Es wird nicht gelöscht, wenn BatchClient verworfen wird.</param>
        <summary>
            Blockierenden Aufruf, der eine Instanz erstellt <see cref="T:Microsoft.Azure.Batch.BatchClient" /> verknüpft sind, mit dem angegebenen <see cref="T:Microsoft.Azure.Batch.Protocol.BatchServiceClient" />.
            </summary>
        <returns>Eine Instanz von <see cref="T:Microsoft.Azure.Batch.Protocol.BatchServiceClient" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.BatchClient&gt; OpenAsync (Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.BatchClient&gt; OpenAsync(class Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClient.OpenAsync(Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function OpenAsync (credentials As BatchSharedKeyCredentials) As Task(Of BatchClient)" />
      <MemberSignature Language="F#" Value="static member OpenAsync : Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.BatchClient&gt;" Usage="Microsoft.Azure.Batch.BatchClient.OpenAsync credentials" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.BatchClient&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.Batch.Auth.BatchSharedKeyCredentials" />
      </Parameters>
      <Docs>
        <param name="credentials">Die Anmeldeinformationen für den Batch-Konto.</param>
        <summary>
            Erstellt eine Instanz des <see cref="T:Microsoft.Azure.Batch.BatchClient" /> den angegebenen Anmeldeinformationen zugeordnet.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.BatchClient&gt; OpenAsync (Microsoft.Azure.Batch.Auth.BatchTokenCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.BatchClient&gt; OpenAsync(class Microsoft.Azure.Batch.Auth.BatchTokenCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClient.OpenAsync(Microsoft.Azure.Batch.Auth.BatchTokenCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function OpenAsync (credentials As BatchTokenCredentials) As Task(Of BatchClient)" />
      <MemberSignature Language="F#" Value="static member OpenAsync : Microsoft.Azure.Batch.Auth.BatchTokenCredentials -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.BatchClient&gt;" Usage="Microsoft.Azure.Batch.BatchClient.OpenAsync credentials" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.BatchClient&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="credentials" Type="Microsoft.Azure.Batch.Auth.BatchTokenCredentials" />
      </Parameters>
      <Docs>
        <param name="credentials">Die Anmeldeinformationen für den Azure Active Directory-Batch-Konto.</param>
        <summary>
            Erstellt eine Instanz von <see cref="T:Microsoft.Azure.Batch.BatchClient" />.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OpenAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.BatchClient&gt; OpenAsync (Microsoft.Azure.Batch.Protocol.BatchServiceClient restClient);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Batch.BatchClient&gt; OpenAsync(class Microsoft.Azure.Batch.Protocol.BatchServiceClient restClient) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.BatchClient.OpenAsync(Microsoft.Azure.Batch.Protocol.BatchServiceClient)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function OpenAsync (restClient As BatchServiceClient) As Task(Of BatchClient)" />
      <MemberSignature Language="F#" Value="static member OpenAsync : Microsoft.Azure.Batch.Protocol.BatchServiceClient -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.BatchClient&gt;" Usage="Microsoft.Azure.Batch.BatchClient.OpenAsync restClient" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Batch.BatchClient&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="restClient" Type="Microsoft.Azure.Batch.Protocol.BatchServiceClient" />
      </Parameters>
      <Docs>
        <param name="restClient">Die Instanz von <see cref="T:Microsoft.Azure.Batch.Protocol.BatchServiceClient" /> für alle Aufrufe an die Batch-Dienst verwendet. Es wird nicht gelöscht, wenn BatchClient verworfen wird.</param>
        <summary>
            Erstellt eine Instanz des <see cref="T:Microsoft.Azure.Batch.BatchClient" /> verknüpft sind, mit dem angegebenen <see cref="T:Microsoft.Azure.Batch.Protocol.BatchServiceClient" />.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PoolOperations">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.PoolOperations PoolOperations { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.PoolOperations PoolOperations" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchClient.PoolOperations" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PoolOperations As PoolOperations" />
      <MemberSignature Language="F#" Value="member this.PoolOperations : Microsoft.Azure.Batch.PoolOperations" Usage="Microsoft.Azure.Batch.BatchClient.PoolOperations" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.PoolOperations</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine <see cref="P:Microsoft.Azure.Batch.BatchClient.PoolOperations" /> für Pool-bezogenen Vorgänge für das zugeordnete Konto ausführen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Utilities">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Utilities Utilities { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Utilities Utilities" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.BatchClient.Utilities" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Utilities As Utilities" />
      <MemberSignature Language="F#" Value="member this.Utilities : Microsoft.Azure.Batch.Utilities" Usage="Microsoft.Azure.Batch.BatchClient.Utilities" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Utilities</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft eine <see cref="P:Microsoft.Azure.Batch.BatchClient.Utilities" /> Objekt, das Hilfsmethoden für die Orchestrierung mehrere Batchvorgänge enthält.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>