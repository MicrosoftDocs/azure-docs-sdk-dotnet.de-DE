<Type Name="MessagingExceptionDetail" FullName="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail">
  <TypeSignature Language="C#" Value="public sealed class MessagingExceptionDetail" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit MessagingExceptionDetail extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MessagingExceptionDetail" />
  <TypeSignature Language="F#" Value="type MessagingExceptionDetail = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceBus</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Enthält die Details der messaging-Ausnahme.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CorrelationFiltersExceeded">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail CorrelationFiltersExceeded (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail CorrelationFiltersExceeded(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.CorrelationFiltersExceeded(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CorrelationFiltersExceeded (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member CorrelationFiltersExceeded : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.CorrelationFiltersExceeded message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Eine beschreibende Meldung zur Ausnahme.</param>
        <summary>Gibt die Details der Ausnahme für die korrelationsfilter überschritten (Fehler).</summary>
        <returns>Die Ausnahmedetails der korrelationsfilter überschritten (Fehler).</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DataCommunicationError">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail DataCommunicationError (string entityName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail DataCommunicationError(string entityName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.DataCommunicationError(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function DataCommunicationError (entityName As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member DataCommunicationError : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.DataCommunicationError entityName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityName"></param>
        <summary />
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityConflict">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EntityConflict (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EntityConflict(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EntityConflict(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EntityConflict (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member EntityConflict : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EntityConflict message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Eine beschreibende Meldung zur Ausnahme.</param>
        <summary>Gibt die Details der Ausnahme für die Entität Konfliktfehler zurück.</summary>
        <returns>Die Ausnahmedetails der Konfliktfehler Entität.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityConflictOperationInProgress">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EntityConflictOperationInProgress (string entityName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EntityConflictOperationInProgress(string entityName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EntityConflictOperationInProgress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EntityConflictOperationInProgress (entityName As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member EntityConflictOperationInProgress : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EntityConflictOperationInProgress entityName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityName">Der Name der messaging-Entität.</param>
        <summary>Gibt die Ausnahmedetails für einen Konflikt für Entität im Status Fehler zurück. Dies kann auftreten, wenn bereits eine widersprüchliche erstellen oder löschen ausstehender Aufruf, für die betreffende Entität.</summary>
        <returns>Gibt <see cref="T:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityGone">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EntityGone (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EntityGone(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EntityGone(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EntityGone (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member EntityGone : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EntityGone message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Eine beschreibende Meldung zur Ausnahme.</param>
        <summary>Gibt die Details der Ausnahme für die Entität fehlend-Fehler zurück.</summary>
        <returns>Die Details der Ausnahme für die Entität fehlend Fehler.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityNotFound">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EntityNotFound (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EntityNotFound(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EntityNotFound(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EntityNotFound (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member EntityNotFound : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EntityNotFound message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Eine beschreibende Meldung zur Ausnahme.</param>
        <summary>Gibt die Details der Ausnahme für die Entität nicht gefunden-Fehler zurück.</summary>
        <returns>Die Details der Ausnahme für die Entität wurde nicht gefunden.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityUpdateConflict">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EntityUpdateConflict (string entityName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EntityUpdateConflict(string entityName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EntityUpdateConflict(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EntityUpdateConflict (entityName As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member EntityUpdateConflict : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EntityUpdateConflict entityName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityName">Der Name der Entität.</param>
        <summary>Gibt die Details der Ausnahme für die Entität Update-Konflikt-Fehler zurück.</summary>
        <returns>Die Details der Ausnahme für die Entität aktualisieren Konfliktfehler.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorCode">
      <MemberSignature Language="C#" Value="public int ErrorCode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ErrorCode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorCode As Integer" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : int" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.ErrorCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den Fehlercode ab.</summary>
        <value>Der Fehlercode.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ErrorLevel">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.ErrorLevelType ErrorLevel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.ServiceBus.Messaging.MessagingExceptionDetail/ErrorLevelType ErrorLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.ErrorLevel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorLevel As MessagingExceptionDetail.ErrorLevelType" />
      <MemberSignature Language="F#" Value="member this.ErrorLevel : Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.ErrorLevelType" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.ErrorLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail+ErrorLevelType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Fehlerebene ab.</summary>
        <value>Einer der Werte von der <see cref="T:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.ErrorLevelType" /> Enumeration.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubAtFullCapacity">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EventHubAtFullCapacity (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail EventHubAtFullCapacity(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EventHubAtFullCapacity(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EventHubAtFullCapacity (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member EventHubAtFullCapacity : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.EventHubAtFullCapacity message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Eine beschreibende Meldung zur Ausnahme.</param>
        <summary>Gibt die Details der Ausnahme bei einem Event Hub wird mit voller Kapazität. </summary>
        <returns>Gibt <see cref="T:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft den beschreibenden Meldung zur Ausnahme ab.</summary>
        <value>Die beschreibenden Meldung zur Ausnahme.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublisherRevoked">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail PublisherRevoked (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail PublisherRevoked(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.PublisherRevoked(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function PublisherRevoked (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member PublisherRevoked : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.PublisherRevoked message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Eine beschreibende Meldung zur Ausnahme.</param>
        <summary>Gibt die Details der Ausnahme bei einem Event Hubs-Verleger wurde gesperrt.</summary>
        <returns>Gibt <see cref="T:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" />zurück.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerBusy">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail ServerBusy (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail ServerBusy(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.ServerBusy(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ServerBusy (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member ServerBusy : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.ServerBusy message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Eine beschreibende Meldung zur Ausnahme.</param>
        <summary>Gibt die Details der Ausnahme für den Server ausgelastet-Fehler zurück.</summary>
        <returns>Die Ausnahmedetails der Server ausgelastet-Fehler.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlFiltersExceeded">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail SqlFiltersExceeded (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail SqlFiltersExceeded(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.SqlFiltersExceeded(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SqlFiltersExceeded (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member SqlFiltersExceeded : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.SqlFiltersExceeded message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Eine beschreibende Meldung zur Ausnahme.</param>
        <summary>Gibt die Details der Ausnahme für die SQL-Filter überschritten (Fehler).</summary>
        <returns>Die Details der Ausnahme für die SQL-Filter überschritten (Fehler).</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreLockLost">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail StoreLockLost (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail StoreLockLost(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.StoreLockLost(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function StoreLockLost (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member StoreLockLost : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.StoreLockLost message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Eine beschreibende Meldung zur Ausnahme.</param>
        <summary>Gibt die Details der Ausnahme für den Speicher gesperrt werden, Fehler verloren.</summary>
        <returns>Die Details der Ausnahme für den Speicher gesperrt werden Fehler verloren.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionsExceeded">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail SubscriptionsExceeded (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail SubscriptionsExceeded(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.SubscriptionsExceeded(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SubscriptionsExceeded (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member SubscriptionsExceeded : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.SubscriptionsExceeded message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Eine beschreibende Meldung zur Ausnahme.</param>
        <summary>Gibt die Details der Ausnahme für die Abonnements überschritten (Fehler).</summary>
        <returns>Die Details der Ausnahme für die Abonnements überschritten (Fehler).</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnknownDetail">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail UnknownDetail (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail UnknownDetail(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.UnknownDetail(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UnknownDetail (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member UnknownDetail : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.UnknownDetail message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Eine beschreibende Meldung zur Ausnahme.</param>
        <summary>Gibt die Details der Ausnahme für den unbekannten ausführlich-Fehler zurück.</summary>
        <returns>Die Ausnahmedetails der unbekannten ausführlich-Fehler.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnspecifiedInternalError">
      <MemberSignature Language="C#" Value="public static Microsoft.ServiceBus.Messaging.MessagingExceptionDetail UnspecifiedInternalError (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.ServiceBus.Messaging.MessagingExceptionDetail UnspecifiedInternalError(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.UnspecifiedInternalError(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UnspecifiedInternalError (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member UnspecifiedInternalError : string -&gt; Microsoft.ServiceBus.Messaging.MessagingExceptionDetail" Usage="Microsoft.ServiceBus.Messaging.MessagingExceptionDetail.UnspecifiedInternalError message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceBus</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceBus.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Eine beschreibende Meldung zur Ausnahme.</param>
        <summary>Gibt die Ausnahmedetails der nicht angegebene interne Fehler zurück.</summary>
        <returns>Die Ausnahmedetails der nicht angegebene interne Fehler.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>