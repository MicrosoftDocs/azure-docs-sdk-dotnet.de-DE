<Type Name="MessagingExceptionDetail" FullName="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail">
  <TypeSignature Language="C#" Value="public sealed class MessagingExceptionDetail" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi serializable sealed beforefieldinit MessagingExceptionDetail extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class MessagingExceptionDetail" />
  <TypeSignature Language="F#" Value="type MessagingExceptionDetail = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail CorrelationFiltersExceeded (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail CorrelationFiltersExceeded(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.CorrelationFiltersExceeded(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function CorrelationFiltersExceeded (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member CorrelationFiltersExceeded : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.CorrelationFiltersExceeded message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Die beschreibenden Meldung zur Ausnahme.</param>
        <summary>Gibt die Details der Ausnahme für die korrelationsfilter überschritten (Fehler).</summary>
        <returns>Die Ausnahmedetails der korrelationsfilter überschritten (Fehler).</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityConflict">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail EntityConflict (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail EntityConflict(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.EntityConflict(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EntityConflict (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member EntityConflict : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.EntityConflict message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Die beschreibenden Meldung zur Ausnahme.</param>
        <summary>Gibt die Details der Ausnahme für die Entität Konfliktfehler zurück.</summary>
        <returns>Die Ausnahmedetails der Konfliktfehler Entität.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityConflictOperationInProgress">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail EntityConflictOperationInProgress (string entityName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail EntityConflictOperationInProgress(string entityName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.EntityConflictOperationInProgress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EntityConflictOperationInProgress (entityName As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member EntityConflictOperationInProgress : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.EntityConflictOperationInProgress entityName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="entityName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="entityName">Der Name der Entität.</param>
        <summary>
            Erstellt eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" /> Klasse mit dem Fehlercode ConflictOperationInProgress.
            </summary>
        <returns>
            Die Ausnahmeinstanz-Klasse
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityGone">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail EntityGone (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail EntityGone(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.EntityGone(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EntityGone (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member EntityGone : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.EntityGone message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Die beschreibenden Meldung zur Ausnahme.</param>
        <summary>Gibt die Details der Ausnahme für die Entität fehlend-Fehler zurück.</summary>
        <returns>Die Details der Ausnahme für die Entität fehlend Fehler.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityNotFound">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail EntityNotFound (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail EntityNotFound(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.EntityNotFound(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EntityNotFound (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member EntityNotFound : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.EntityNotFound message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Die beschreibenden Meldung zur Ausnahme.</param>
        <summary>Gibt die Details der Ausnahme für die Entität nicht gefunden-Fehler zurück.</summary>
        <returns>Die Details der Ausnahme für die Entität wurde nicht gefunden.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EntityUpdateConflict">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail EntityUpdateConflict (string entityName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail EntityUpdateConflict(string entityName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.EntityUpdateConflict(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EntityUpdateConflict (entityName As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member EntityUpdateConflict : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.EntityUpdateConflict entityName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail</ReturnType>
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
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.ErrorCode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorCode As Integer" />
      <MemberSignature Language="F#" Value="member this.ErrorCode : int" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.ErrorCode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.ErrorLevelType ErrorLevel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail/ErrorLevelType ErrorLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.ErrorLevel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ErrorLevel As MessagingExceptionDetail.ErrorLevelType" />
      <MemberSignature Language="F#" Value="member this.ErrorLevel : Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.ErrorLevelType" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.ErrorLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail+ErrorLevelType</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft die Fehlerebene ab.</summary>
        <value>Einer der Werte von der <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.ErrorLevelType" /> Enumeration.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EventHubAtFullCapacity">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail EventHubAtFullCapacity (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail EventHubAtFullCapacity(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.EventHubAtFullCapacity(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function EventHubAtFullCapacity (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member EventHubAtFullCapacity : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.EventHubAtFullCapacity message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Die Ausnahmemeldung.</param>
        <summary>
            Erstellt eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" /> Klasse mit dem Fehlercode EventHubAtFullCapacity.
            </summary>
        <returns>Die Ausnahmeinstanz-Klasse</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Message">
      <MemberSignature Language="C#" Value="public string Message { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Message" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.Message" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Message As String" />
      <MemberSignature Language="F#" Value="member this.Message : string" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.Message" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
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
    <Member MemberName="ReconstructExceptionDetail">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail ReconstructExceptionDetail (int errorCode, string message, Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.ErrorLevelType errorLevel);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail ReconstructExceptionDetail(int32 errorCode, string message, valuetype Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail/ErrorLevelType errorLevel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.ReconstructExceptionDetail(System.Int32,System.String,Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.ErrorLevelType)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ReconstructExceptionDetail (errorCode As Integer, message As String, errorLevel As MessagingExceptionDetail.ErrorLevelType) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member ReconstructExceptionDetail : int * string * Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.ErrorLevelType -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.ReconstructExceptionDetail (errorCode, message, errorLevel)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="errorCode" Type="System.Int32" />
        <Parameter Name="message" Type="System.String" />
        <Parameter Name="errorLevel" Type="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail+ErrorLevelType" />
      </Parameters>
      <Docs>
        <param name="errorCode">Der Fehlercode.</param>
        <param name="message">Die Ausnahmemeldung.</param>
        <param name="errorLevel">Die Fehlerebene.</param>
        <summary>
            Erstellt eine neue Instanz der dem <see cref="T:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" /> Klasse mit einem benutzerdefinierten Fehlercode.
            </summary>
        <returns>
            Die Ausnahmeinstanz-Klasse
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServerBusy">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail ServerBusy (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail ServerBusy(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.ServerBusy(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function ServerBusy (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member ServerBusy : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.ServerBusy message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Die beschreibenden Meldung zur Ausnahme.</param>
        <summary>Gibt die Details der Ausnahme für den Server ausgelastet-Fehler zurück.</summary>
        <returns>Die Ausnahmedetails der Server ausgelastet-Fehler.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlFiltersExceeded">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail SqlFiltersExceeded (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail SqlFiltersExceeded(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.SqlFiltersExceeded(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SqlFiltersExceeded (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member SqlFiltersExceeded : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.SqlFiltersExceeded message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Die beschreibenden Meldung zur Ausnahme.</param>
        <summary>Gibt die Details der Ausnahme für die SQL-Filter überschritten (Fehler).</summary>
        <returns>Die Details der Ausnahme für die SQL-Filter überschritten (Fehler).</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StoreLockLost">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail StoreLockLost (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail StoreLockLost(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.StoreLockLost(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function StoreLockLost (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member StoreLockLost : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.StoreLockLost message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Die beschreibenden Meldung zur Ausnahme.</param>
        <summary>Gibt die Details der Ausnahme für den Speicher gesperrt werden, Fehler verloren.</summary>
        <returns>Die Details der Ausnahme für den Speicher gesperrt werden Fehler verloren.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubscriptionsExceeded">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail SubscriptionsExceeded (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail SubscriptionsExceeded(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.SubscriptionsExceeded(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function SubscriptionsExceeded (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member SubscriptionsExceeded : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.SubscriptionsExceeded message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Die beschreibenden Meldung zur Ausnahme.</param>
        <summary>Gibt die Details der Ausnahme für die Abonnements überschritten (Fehler).</summary>
        <returns>Die Details der Ausnahme für die Abonnements überschritten (Fehler).</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnknownDetail">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail UnknownDetail (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail UnknownDetail(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.UnknownDetail(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UnknownDetail (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member UnknownDetail : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.UnknownDetail message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Die beschreibenden Meldung zur Ausnahme.</param>
        <summary>Gibt die Details der Ausnahme für den unbekannten ausführlich-Fehler zurück.</summary>
        <returns>Die Ausnahmedetails der unbekannten ausführlich-Fehler.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnspecifiedInternalError">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail UnspecifiedInternalError (string message);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail UnspecifiedInternalError(string message) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.UnspecifiedInternalError(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function UnspecifiedInternalError (message As String) As MessagingExceptionDetail" />
      <MemberSignature Language="F#" Value="static member UnspecifiedInternalError : string -&gt; Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail" Usage="Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail.UnspecifiedInternalError message" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.NotificationHubs.Messaging.MessagingExceptionDetail</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="message" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="message">Die beschreibenden Meldung zur Ausnahme.</param>
        <summary>Gibt die Ausnahmedetails der nicht angegebene interne Fehler zurück.</summary>
        <returns>Die Ausnahmedetails der nicht angegebene interne Fehler.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>