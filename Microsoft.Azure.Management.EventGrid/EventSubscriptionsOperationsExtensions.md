<Type Name="EventSubscriptionsOperationsExtensions" FullName="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class EventSubscriptionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit EventSubscriptionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module EventSubscriptionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type EventSubscriptionsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für EventSubscriptionsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.EventSubscription BeginCreate (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.EventSubscription BeginCreate(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginCreate(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscription)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function BeginCreate (operations As IEventSubscriptionsOperations, scope As String, eventSubscriptionName As String, eventSubscriptionInfo As EventSubscription) As EventSubscription" />
      <MemberSignature Language="F#" Value="static member BeginCreate : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscription -&gt; Microsoft.Azure.Management.EventGrid.Models.EventSubscription" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginCreate (operations, scope, eventSubscriptionName, eventSubscriptionInfo)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.EventSubscription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionInfo" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscription" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="scope">
            Der Bereich der Ressource, die das Ereignisabonnement erstellt werden muss. Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein. Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.
            </param>
        <param name="eventSubscriptionName">
            Name des Ereignisses Abonnements erstellt werden soll. Abonnement Ereignisnamen müssen zwischen 3 und 64 Zeichen lang sein und nur alphanumerische Buchstaben verwenden.
            </param>
        <param name="eventSubscriptionInfo">
            Ereigniseigenschaften-Abonnement mit Informationen über das Ziel und filter
            </param>
        <summary>
            Ereignisabonnement erstellen
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Erstellt asynchron ein neues Ereignisabonnement im angegebenen Bereich.
            Vorhandene Ereignisabonnements können nicht mit dieser API aktualisiert werden und das Ereignisabonnement Update API sollte stattdessen verwendet werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; BeginCreateAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; BeginCreateAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginCreateAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscription,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginCreateAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscription * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginCreateAsync (operations, scope, eventSubscriptionName, eventSubscriptionInfo, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;BeginCreateAsync&gt;d__29))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionInfo" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscription" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="scope">
            Der Bereich der Ressource, die das Ereignisabonnement erstellt werden muss. Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein. Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.
            </param>
        <param name="eventSubscriptionName">
            Name des Ereignisses Abonnements erstellt werden soll. Abonnement Ereignisnamen müssen zwischen 3 und 64 Zeichen lang sein und nur alphanumerische Buchstaben verwenden.
            </param>
        <param name="eventSubscriptionInfo">
            Ereigniseigenschaften-Abonnement mit Informationen über das Ziel und filter
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ereignisabonnement erstellen
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Erstellt asynchron ein neues Ereignisabonnement im angegebenen Bereich.
            Vorhandene Ereignisabonnements können nicht mit dieser API aktualisiert werden und das Ereignisabonnement Update API sollte stattdessen verwendet werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public static void BeginDelete (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void BeginDelete(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginDelete(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub BeginDelete (operations As IEventSubscriptionsOperations, scope As String, eventSubscriptionName As String)" />
      <MemberSignature Language="F#" Value="static member BeginDelete : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginDelete (operations, scope, eventSubscriptionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="scope">
            Der Bereich der Abonnieren des Ereignisses. Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein. Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.
            </param>
        <param name="eventSubscriptionName">
            Name des das Ereignisabonnement
            </param>
        <summary>
            Ereignisabonnement löschen
            </summary>
        <remarks>
            Löschen Sie ein vorhandenes Ereignisabonnement
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task BeginDeleteAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task BeginDeleteAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginDeleteAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginDeleteAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginDeleteAsync (operations, scope, eventSubscriptionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;BeginDeleteAsync&gt;d__31))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="scope">
            Der Bereich der Abonnieren des Ereignisses. Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein. Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.
            </param>
        <param name="eventSubscriptionName">
            Name des das Ereignisabonnement
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ereignisabonnement löschen
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Löschen Sie ein vorhandenes Ereignisabonnement
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdate">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.EventSubscription BeginUpdate (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.EventSubscription BeginUpdate(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginUpdate(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters)" />
      <MemberSignature Language="F#" Value="static member BeginUpdate : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters -&gt; Microsoft.Azure.Management.EventGrid.Models.EventSubscription" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginUpdate (operations, scope, eventSubscriptionName, eventSubscriptionUpdateParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.EventSubscription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionUpdateParameters" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="scope">
            Der Bereich der vorhandenen Ereignisabonnement. Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein. Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.
            </param>
        <param name="eventSubscriptionName">
            Name des zu erstellenden das Ereignisabonnement
            </param>
        <param name="eventSubscriptionUpdateParameters">
            Aktualisierte Ereignisinformationen für Abonnement
            </param>
        <summary>
            Ereignisabonnement aktualisieren
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Aktualisiert asynchron eine vorhandene Ereignisabonnement aus.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginUpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; BeginUpdateAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; BeginUpdateAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginUpdateAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member BeginUpdateAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.BeginUpdateAsync (operations, scope, eventSubscriptionName, eventSubscriptionUpdateParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;BeginUpdateAsync&gt;d__33))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionUpdateParameters" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="scope">
            Der Bereich der vorhandenen Ereignisabonnement. Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein. Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.
            </param>
        <param name="eventSubscriptionName">
            Name des zu erstellenden das Ereignisabonnement
            </param>
        <param name="eventSubscriptionUpdateParameters">
            Aktualisierte Ereignisinformationen für Abonnement
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ereignisabonnement aktualisieren
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Aktualisiert asynchron eine vorhandene Ereignisabonnement aus.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.EventSubscription Create (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.EventSubscription Create(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.Create(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscription)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Create (operations As IEventSubscriptionsOperations, scope As String, eventSubscriptionName As String, eventSubscriptionInfo As EventSubscription) As EventSubscription" />
      <MemberSignature Language="F#" Value="static member Create : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscription -&gt; Microsoft.Azure.Management.EventGrid.Models.EventSubscription" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.Create (operations, scope, eventSubscriptionName, eventSubscriptionInfo)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.EventSubscription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionInfo" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscription" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="scope">
            Der Bereich der Ressource, die das Ereignisabonnement erstellt werden muss. Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein. Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.
            </param>
        <param name="eventSubscriptionName">
            Name des Ereignisses Abonnements erstellt werden soll. Abonnement Ereignisnamen müssen zwischen 3 und 64 Zeichen lang sein und nur alphanumerische Buchstaben verwenden.
            </param>
        <param name="eventSubscriptionInfo">
            Ereigniseigenschaften-Abonnement mit Informationen über das Ziel und filter
            </param>
        <summary>
            Ereignisabonnement erstellen
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Erstellt asynchron ein neues Ereignisabonnement im angegebenen Bereich.
            Vorhandene Ereignisabonnements können nicht mit dieser API aktualisiert werden und das Ereignisabonnement Update API sollte stattdessen verwendet werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; CreateAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; CreateAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscription eventSubscriptionInfo, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.CreateAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscription,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member CreateAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscription * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.CreateAsync (operations, scope, eventSubscriptionName, eventSubscriptionInfo, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;CreateAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionInfo" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscription" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="scope">
            Der Bereich der Ressource, die das Ereignisabonnement erstellt werden muss. Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein. Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.
            </param>
        <param name="eventSubscriptionName">
            Name des Ereignisses Abonnements erstellt werden soll. Abonnement Ereignisnamen müssen zwischen 3 und 64 Zeichen lang sein und nur alphanumerische Buchstaben verwenden.
            </param>
        <param name="eventSubscriptionInfo">
            Ereigniseigenschaften-Abonnement mit Informationen über das Ziel und filter
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ereignisabonnement erstellen
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Erstellt asynchron ein neues Ereignisabonnement im angegebenen Bereich.
            Vorhandene Ereignisabonnements können nicht mit dieser API aktualisiert werden und das Ereignisabonnement Update API sollte stattdessen verwendet werden.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public static void Delete (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig void Delete(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.Delete(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Sub Delete (operations As IEventSubscriptionsOperations, scope As String, eventSubscriptionName As String)" />
      <MemberSignature Language="F#" Value="static member Delete : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string -&gt; unit" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.Delete (operations, scope, eventSubscriptionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="scope">
            Der Bereich der Abonnieren des Ereignisses. Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein. Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.
            </param>
        <param name="eventSubscriptionName">
            Name des das Ereignisabonnement
            </param>
        <summary>
            Ereignisabonnement löschen
            </summary>
        <remarks>
            Löschen Sie ein vorhandenes Ereignisabonnement
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DeleteAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.DeleteAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DeleteAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.DeleteAsync (operations, scope, eventSubscriptionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;DeleteAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="scope">
            Der Bereich der Abonnieren des Ereignisses. Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein. Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.
            </param>
        <param name="eventSubscriptionName">
            Name des das Ereignisabonnement
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ereignisabonnement löschen
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Löschen Sie ein vorhandenes Ereignisabonnement
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.EventSubscription Get (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.EventSubscription Get(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.Get(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IEventSubscriptionsOperations, scope As String, eventSubscriptionName As String) As EventSubscription" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string -&gt; Microsoft.Azure.Management.EventGrid.Models.EventSubscription" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.Get (operations, scope, eventSubscriptionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.EventSubscription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="scope">
            Der Bereich der Abonnieren des Ereignisses. Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein. Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.
            </param>
        <param name="eventSubscriptionName">
            Name des das Ereignisabonnement
            </param>
        <summary>
            Ereignisabonnement abrufen
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Abrufen von Eigenschaften von Ereignisabonnement
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; GetAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; GetAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.GetAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.GetAsync (operations, scope, eventSubscriptionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;GetAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="scope">
            Der Bereich der Abonnieren des Ereignisses. Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein. Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.
            </param>
        <param name="eventSubscriptionName">
            Name des das Ereignisabonnement
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ereignisabonnement abrufen
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Abrufen von Eigenschaften von Ereignisabonnement
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFullUrl">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl GetFullUrl (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl GetFullUrl(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.GetFullUrl(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetFullUrl (operations As IEventSubscriptionsOperations, scope As String, eventSubscriptionName As String) As EventSubscriptionFullUrl" />
      <MemberSignature Language="F#" Value="static member GetFullUrl : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string -&gt; Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.GetFullUrl (operations, scope, eventSubscriptionName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="scope">
            Der Bereich der Abonnieren des Ereignisses. Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein. Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.
            </param>
        <param name="eventSubscriptionName">
            Name des das Ereignisabonnement
            </param>
        <summary>
            Vollständige URL des Ereignisabonnement abrufen
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Rufen Sie die vollständige Endpunkt-URL für Ereignisabonnement
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetFullUrlAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl&gt; GetFullUrlAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl&gt; GetFullUrlAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.GetFullUrlAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetFullUrlAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.GetFullUrlAsync (operations, scope, eventSubscriptionName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;GetFullUrlAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionFullUrl&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="scope">
            Der Bereich der Abonnieren des Ereignisses. Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein. Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.
            </param>
        <param name="eventSubscriptionName">
            Name des das Ereignisabonnement
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Vollständige URL des Ereignisabonnement abrufen
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Rufen Sie die vollständige Endpunkt-URL für Ereignisabonnement
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResource">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListByResource (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string providerNamespace, string resourceTypeName, string resourceName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListByResource(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string providerNamespace, string resourceTypeName, string resourceName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListByResource(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListByResource (operations As IEventSubscriptionsOperations, resourceGroupName As String, providerNamespace As String, resourceTypeName As String, resourceName As String) As IEnumerable(Of EventSubscription)" />
      <MemberSignature Language="F#" Value="static member ListByResource : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListByResource (operations, resourceGroupName, providerNamespace, resourceTypeName, resourceName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="providerNamespace" Type="System.String" />
        <Parameter Name="resourceTypeName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.
            </param>
        <param name="providerNamespace">
            Namespace des Anbieters des Themas
            </param>
        <param name="resourceTypeName">
            Name des Ressourcentyps
            </param>
        <param name="resourceName">
            Name der Ressource
            </param>
        <summary>
            Listen Sie aller Ereignisabonnements, für ein bestimmtes Thema auf
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Listen Sie aller Ereignisabonnements auf,, die für ein bestimmtes Thema erstellt wurden
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListByResourceAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListByResourceAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string providerNamespace, string resourceTypeName, string resourceName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListByResourceAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string providerNamespace, string resourceTypeName, string resourceName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListByResourceAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListByResourceAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListByResourceAsync (operations, resourceGroupName, providerNamespace, resourceTypeName, resourceName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;ListByResourceAsync&gt;d__27))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="providerNamespace" Type="System.String" />
        <Parameter Name="resourceTypeName" Type="System.String" />
        <Parameter Name="resourceName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.
            </param>
        <param name="providerNamespace">
            Namespace des Anbieters des Themas
            </param>
        <param name="resourceTypeName">
            Name des Ressourcentyps
            </param>
        <param name="resourceName">
            Name der Ressource
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listen Sie aller Ereignisabonnements, für ein bestimmtes Thema auf
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Listen Sie aller Ereignisabonnements auf,, die für ein bestimmtes Thema erstellt wurden
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGlobalByResourceGroup">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListGlobalByResourceGroup (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListGlobalByResourceGroup(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalByResourceGroup(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListGlobalByResourceGroup (operations As IEventSubscriptionsOperations, resourceGroupName As String) As IEnumerable(Of EventSubscription)" />
      <MemberSignature Language="F#" Value="static member ListGlobalByResourceGroup : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalByResourceGroup (operations, resourceGroupName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.
            </param>
        <summary>
            Listen Sie aller globalen Ereignisabonnements unter Azure Abonnement- und Ressourcenstatus-Gruppe auf
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Listen Sie aller Abonnements, globale Ereignis unter einer bestimmten Gruppe für Azure Abonnement- und Ressourcenstatus auf
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGlobalByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListGlobalByResourceGroupAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListGlobalByResourceGroupAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalByResourceGroupAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListGlobalByResourceGroupAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalByResourceGroupAsync (operations, resourceGroupName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;ListGlobalByResourceGroupAsync&gt;d__15))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listen Sie aller globalen Ereignisabonnements unter Azure Abonnement- und Ressourcenstatus-Gruppe auf
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Listen Sie aller Abonnements, globale Ereignis unter einer bestimmten Gruppe für Azure Abonnement- und Ressourcenstatus auf
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGlobalByResourceGroupForTopicType">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListGlobalByResourceGroupForTopicType (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string topicTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListGlobalByResourceGroupForTopicType(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string topicTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalByResourceGroupForTopicType(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListGlobalByResourceGroupForTopicType (operations As IEventSubscriptionsOperations, resourceGroupName As String, topicTypeName As String) As IEnumerable(Of EventSubscription)" />
      <MemberSignature Language="F#" Value="static member ListGlobalByResourceGroupForTopicType : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalByResourceGroupForTopicType (operations, resourceGroupName, topicTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.
            </param>
        <param name="topicTypeName">
            Name des Typs Thema
            </param>
        <summary>
            Listen Sie aller Abonnements, globale Ereignis unterhalb einer Ressourcengruppe für ein Thema auf
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Listen Sie aller globalen Ereignisabonnements unterhalb einer Ressourcengruppe für einen bestimmten Thema an auf.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGlobalByResourceGroupForTopicTypeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListGlobalByResourceGroupForTopicTypeAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string topicTypeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListGlobalByResourceGroupForTopicTypeAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string topicTypeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalByResourceGroupForTopicTypeAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListGlobalByResourceGroupForTopicTypeAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalByResourceGroupForTopicTypeAsync (operations, resourceGroupName, topicTypeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;ListGlobalByResourceGroupForTopicTypeAsync&gt;d__17))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="topicTypeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.
            </param>
        <param name="topicTypeName">
            Name des Typs Thema
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listen Sie aller Abonnements, globale Ereignis unterhalb einer Ressourcengruppe für ein Thema auf
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Listen Sie aller globalen Ereignisabonnements unterhalb einer Ressourcengruppe für einen bestimmten Thema an auf.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGlobalBySubscription">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListGlobalBySubscription (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListGlobalBySubscription(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalBySubscription(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListGlobalBySubscription (operations As IEventSubscriptionsOperations) As IEnumerable(Of EventSubscription)" />
      <MemberSignature Language="F#" Value="static member ListGlobalBySubscription : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalBySubscription operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <summary>
            Eine aggregierte Liste aller globalen Ereignis Abonnements unter einem Azure-Abonnement abrufen
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Liste aller aggregiert globale Ereignisabonnements unter einem bestimmten Azure-Abonnement
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGlobalBySubscriptionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListGlobalBySubscriptionAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListGlobalBySubscriptionAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalBySubscriptionAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListGlobalBySubscriptionAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalBySubscriptionAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;ListGlobalBySubscriptionAsync&gt;d__11))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Eine aggregierte Liste aller globalen Ereignis Abonnements unter einem Azure-Abonnement abrufen
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Liste aller aggregiert globale Ereignisabonnements unter einem bestimmten Azure-Abonnement
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGlobalBySubscriptionForTopicType">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListGlobalBySubscriptionForTopicType (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string topicTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListGlobalBySubscriptionForTopicType(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string topicTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalBySubscriptionForTopicType(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListGlobalBySubscriptionForTopicType (operations As IEventSubscriptionsOperations, topicTypeName As String) As IEnumerable(Of EventSubscription)" />
      <MemberSignature Language="F#" Value="static member ListGlobalBySubscriptionForTopicType : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalBySubscriptionForTopicType (operations, topicTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="topicTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="topicTypeName">
            Name des Typs Thema
            </param>
        <summary>
            Listen Sie aller Abonnements, globale Ereignis für ein Thema auf
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Listen Sie aller globalen Ereignisabonnements unter einem Azure-Abonnement für ein Thema auf.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListGlobalBySubscriptionForTopicTypeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListGlobalBySubscriptionForTopicTypeAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string topicTypeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListGlobalBySubscriptionForTopicTypeAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string topicTypeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalBySubscriptionForTopicTypeAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListGlobalBySubscriptionForTopicTypeAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListGlobalBySubscriptionForTopicTypeAsync (operations, topicTypeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;ListGlobalBySubscriptionForTopicTypeAsync&gt;d__13))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="topicTypeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="topicTypeName">
            Name des Typs Thema
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listen Sie aller Abonnements, globale Ereignis für ein Thema auf
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Listen Sie aller globalen Ereignisabonnements unter einem Azure-Abonnement für ein Thema auf.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRegionalByResourceGroup">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListRegionalByResourceGroup (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string location);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListRegionalByResourceGroup(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalByResourceGroup(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRegionalByResourceGroup (operations As IEventSubscriptionsOperations, resourceGroupName As String, location As String) As IEnumerable(Of EventSubscription)" />
      <MemberSignature Language="F#" Value="static member ListRegionalByResourceGroup : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalByResourceGroup (operations, resourceGroupName, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.
            </param>
        <param name="location">
            Der Name des Speicherorts
            </param>
        <summary>
            Listen Sie aller Ereignisabonnements unter Azure Abonnement- und Ressourcenstatus-Gruppe, Land/Region auf
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Listen Sie aller Ereignisabonnements, aus dem angegebenen Speicherort unter einer bestimmten Gruppe für Azure Abonnement- und Ressourcenstatus auf
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRegionalByResourceGroupAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListRegionalByResourceGroupAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string location, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListRegionalByResourceGroupAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string location, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalByResourceGroupAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRegionalByResourceGroupAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalByResourceGroupAsync (operations, resourceGroupName, location, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;ListRegionalByResourceGroupAsync&gt;d__21))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.
            </param>
        <param name="location">
            Der Name des Speicherorts
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listen Sie aller Ereignisabonnements unter Azure Abonnement- und Ressourcenstatus-Gruppe, Land/Region auf
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Listen Sie aller Ereignisabonnements, aus dem angegebenen Speicherort unter einer bestimmten Gruppe für Azure Abonnement- und Ressourcenstatus auf
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRegionalByResourceGroupForTopicType">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListRegionalByResourceGroupForTopicType (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string location, string topicTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListRegionalByResourceGroupForTopicType(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string location, string topicTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalByResourceGroupForTopicType(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRegionalByResourceGroupForTopicType (operations As IEventSubscriptionsOperations, resourceGroupName As String, location As String, topicTypeName As String) As IEnumerable(Of EventSubscription)" />
      <MemberSignature Language="F#" Value="static member ListRegionalByResourceGroupForTopicType : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * string -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalByResourceGroupForTopicType (operations, resourceGroupName, location, topicTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="topicTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.
            </param>
        <param name="location">
            Der Name des Speicherorts
            </param>
        <param name="topicTypeName">
            Name des Typs Thema
            </param>
        <summary>
            Listen Sie aller Ereignisabonnements, Land/Region unter einer Azure Abonnement- und Ressourcenstatus-Gruppe für ein Thema auf
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Listen Sie aller Ereignisabonnements, aus dem angegebenen Speicherort unter einen bestimmten Azure Abonnement- und Ressourcenstatus Gruppen- und Thema Typ auf
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRegionalByResourceGroupForTopicTypeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListRegionalByResourceGroupForTopicTypeAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string location, string topicTypeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListRegionalByResourceGroupForTopicTypeAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string resourceGroupName, string location, string topicTypeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalByResourceGroupForTopicTypeAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRegionalByResourceGroupForTopicTypeAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalByResourceGroupForTopicTypeAsync (operations, resourceGroupName, location, topicTypeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;ListRegionalByResourceGroupForTopicTypeAsync&gt;d__25))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="topicTypeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe innerhalb des Abonnements des Benutzers.
            </param>
        <param name="location">
            Der Name des Speicherorts
            </param>
        <param name="topicTypeName">
            Name des Typs Thema
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listen Sie aller Ereignisabonnements, Land/Region unter einer Azure Abonnement- und Ressourcenstatus-Gruppe für ein Thema auf
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Listen Sie aller Ereignisabonnements, aus dem angegebenen Speicherort unter einen bestimmten Azure Abonnement- und Ressourcenstatus Gruppen- und Thema Typ auf
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRegionalBySubscription">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListRegionalBySubscription (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string location);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListRegionalBySubscription(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string location) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalBySubscription(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRegionalBySubscription (operations As IEventSubscriptionsOperations, location As String) As IEnumerable(Of EventSubscription)" />
      <MemberSignature Language="F#" Value="static member ListRegionalBySubscription : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalBySubscription (operations, location)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="location">
            Der Name des Speicherorts
            </param>
        <summary>
            Listen Sie aller Ereignisabonnements unter einem Azure-Abonnement, Land/Region auf
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Listen Sie aller Ereignisabonnements, aus dem angegebenen Speicherort unter einer bestimmten Azure-Abonnement auf
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRegionalBySubscriptionAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListRegionalBySubscriptionAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string location, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListRegionalBySubscriptionAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string location, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalBySubscriptionAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRegionalBySubscriptionAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalBySubscriptionAsync (operations, location, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;ListRegionalBySubscriptionAsync&gt;d__19))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="location">
            Der Name des Speicherorts
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listen Sie aller Ereignisabonnements unter einem Azure-Abonnement, Land/Region auf
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Listen Sie aller Ereignisabonnements, aus dem angegebenen Speicherort unter einer bestimmten Azure-Abonnement auf
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRegionalBySubscriptionForTopicType">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListRegionalBySubscriptionForTopicType (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string location, string topicTypeName);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; ListRegionalBySubscriptionForTopicType(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string location, string topicTypeName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalBySubscriptionForTopicType(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListRegionalBySubscriptionForTopicType (operations As IEventSubscriptionsOperations, location As String, topicTypeName As String) As IEnumerable(Of EventSubscription)" />
      <MemberSignature Language="F#" Value="static member ListRegionalBySubscriptionForTopicType : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalBySubscriptionForTopicType (operations, location, topicTypeName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="topicTypeName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="location">
            Der Name des Speicherorts
            </param>
        <param name="topicTypeName">
            Name des Typs Thema
            </param>
        <summary>
            Listen Sie aller Ereignisabonnements unter einem Azure-Abonnement für eine Thementyp, Land/Region auf
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Listen Sie aller Ereignisabonnements aus dem angegebenen Speicherort unter einen bestimmten Azure-Abonnement und Thema Typ an auf.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRegionalBySubscriptionForTopicTypeAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListRegionalBySubscriptionForTopicTypeAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string location, string topicTypeName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt; ListRegionalBySubscriptionForTopicTypeAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string location, string topicTypeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalBySubscriptionForTopicTypeAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRegionalBySubscriptionForTopicTypeAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.ListRegionalBySubscriptionForTopicTypeAsync (operations, location, topicTypeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;ListRegionalBySubscriptionForTopicTypeAsync&gt;d__23))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="location" Type="System.String" />
        <Parameter Name="topicTypeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="location">
            Der Name des Speicherorts
            </param>
        <param name="topicTypeName">
            Name des Typs Thema
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listen Sie aller Ereignisabonnements unter einem Azure-Abonnement für eine Thementyp, Land/Region auf
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Listen Sie aller Ereignisabonnements aus dem angegebenen Speicherort unter einen bestimmten Azure-Abonnement und Thema Typ an auf.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Update">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.EventGrid.Models.EventSubscription Update (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.EventGrid.Models.EventSubscription Update(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.Update(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters)" />
      <MemberSignature Language="F#" Value="static member Update : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters -&gt; Microsoft.Azure.Management.EventGrid.Models.EventSubscription" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.Update (operations, scope, eventSubscriptionName, eventSubscriptionUpdateParameters)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.EventGrid.Models.EventSubscription</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionUpdateParameters" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="scope">
            Der Bereich der vorhandenen Ereignisabonnement. Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein. Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.
            </param>
        <param name="eventSubscriptionName">
            Name des zu erstellenden das Ereignisabonnement
            </param>
        <param name="eventSubscriptionUpdateParameters">
            Aktualisierte Ereignisinformationen für Abonnement
            </param>
        <summary>
            Ereignisabonnement aktualisieren
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Aktualisiert asynchron eine vorhandene Ereignisabonnement aus.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; UpdateAsync (this Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt; UpdateAsync(class Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations operations, string scope, string eventSubscriptionName, class Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters eventSubscriptionUpdateParameters, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.UpdateAsync(Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations,System.String,System.String,Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UpdateAsync : Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations * string * string * Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;" Usage="Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions.UpdateAsync (operations, scope, eventSubscriptionName, eventSubscriptionUpdateParameters, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.EventSubscriptionsOperationsExtensions/&lt;UpdateAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.EventGrid.Models.EventSubscription&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IEventSubscriptionsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="eventSubscriptionName" Type="System.String" />
        <Parameter Name="eventSubscriptionUpdateParameters" Type="Microsoft.Azure.Management.EventGrid.Models.EventSubscriptionUpdateParameters" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="scope">
            Der Bereich der vorhandenen Ereignisabonnement. Der Bereich kann ein Abonnement oder eine Ressourcengruppe oder eine Ressource der obersten Ebene, die zu einem Ressourcenanbieter-Namespace oder ein Thema EventGrid gehören sein. Verwenden Sie z. B. "/ Subscriptions / {SubscriptionId} /" für ein Abonnement, "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName}" für eine Ressourcengruppe, und "/ Subscriptions / {SubscriptionId} / ResourceGroups / {ResourceGroupName} / Anbieter / {ResourceProviderNamespace} / {ResourceType} / {ResourceName} "für eine Ressource und" / subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.EventGrid/topics/{topicName} "für ein Thema EventGrid.
            </param>
        <param name="eventSubscriptionName">
            Name des zu erstellenden das Ereignisabonnement
            </param>
        <param name="eventSubscriptionUpdateParameters">
            Aktualisierte Ereignisinformationen für Abonnement
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ereignisabonnement aktualisieren
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Aktualisiert asynchron eine vorhandene Ereignisabonnement aus.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>