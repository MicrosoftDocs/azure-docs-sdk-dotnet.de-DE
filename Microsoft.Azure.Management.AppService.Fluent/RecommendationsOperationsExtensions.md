<Type Name="RecommendationsOperationsExtensions" FullName="Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class RecommendationsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit RecommendationsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module RecommendationsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type RecommendationsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für RecommendationsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DisableAllForWebAppAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task DisableAllForWebAppAsync (this Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations operations, string resourceGroupName, string siteName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task DisableAllForWebAppAsync(class Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations operations, string resourceGroupName, string siteName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions.DisableAllForWebAppAsync(Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member DisableAllForWebAppAsync : Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions.DisableAllForWebAppAsync (operations, resourceGroupName, siteName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions/&lt;DisableAllForWebAppAsync&gt;d__4))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="siteName">
            Der Name der app.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Deaktivieren Sie alle Empfehlungen für eine app an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Deaktivieren Sie alle Empfehlungen für eine app an.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GetRuleDetailsByWebAppAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationRuleInner&gt; GetRuleDetailsByWebAppAsync (this Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations operations, string resourceGroupName, string siteName, string name, Nullable&lt;bool&gt; updateSeen = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationRuleInner&gt; GetRuleDetailsByWebAppAsync(class Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations operations, string resourceGroupName, string siteName, string name, valuetype System.Nullable`1&lt;bool&gt; updateSeen, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions.GetRuleDetailsByWebAppAsync(Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations,System.String,System.String,System.String,System.Nullable{System.Boolean},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetRuleDetailsByWebAppAsync : Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations * string * string * string * Nullable&lt;bool&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationRuleInner&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions.GetRuleDetailsByWebAppAsync (operations, resourceGroupName, siteName, name, updateSeen, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions/&lt;GetRuleDetailsByWebAppAsync&gt;d__6))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationRuleInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="updateSeen" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="siteName">
            Der Name der app.
            </param>
        <param name="name">
            Der Name der Empfehlung.
            </param>
        <param name="updateSeen">
            Geben Sie &lt;Code&gt;"true"&lt;/code&gt; den letzten gesehen Zeitstempel des Objekts Empfehlung zu aktualisieren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Eine Regel für die Empfehlung für eine app abrufen.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Eine Regel für die Empfehlung für eine app abrufen.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt; ListAsync (this Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations operations, Nullable&lt;bool&gt; featured = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt; ListAsync(class Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations operations, valuetype System.Nullable`1&lt;bool&gt; featured, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions.ListAsync(Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations,System.Nullable{System.Boolean},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations * Nullable&lt;bool&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions.ListAsync (operations, featured, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions/&lt;ListAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations" RefType="this" />
        <Parameter Name="featured" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="featured">
            Geben Sie &lt;Code&gt;"true"&lt;/code&gt; nur die wichtigsten Empfehlungen zurückgegeben. Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;, wobei alle Empfehlungen zurückgegeben.
            </param>
        <param name="filter">
            Filter wird mithilfe von OData-Syntax angegeben. Beispiel: $filter = Kanäle Eq "-Api" oder den Kanal Eq "Benachrichtigung" und "StartTime" Eq "2014-01-01T00:00:00Z" und EndTime-Eq "2014-12-31T23:59:59Z" und die Dauer der timegrain-Wert-Eq "[PT1H | PT1M | P1D]
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Liste aller Empfehlungen für ein Abonnement an.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Liste aller Empfehlungen für ein Abonnement an.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListHistoryForWebAppAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt; ListHistoryForWebAppAsync (this Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations operations, string resourceGroupName, string siteName, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt; ListHistoryForWebAppAsync(class Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations operations, string resourceGroupName, string siteName, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions.ListHistoryForWebAppAsync(Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListHistoryForWebAppAsync : Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions.ListHistoryForWebAppAsync (operations, resourceGroupName, siteName, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions/&lt;ListHistoryForWebAppAsync&gt;d__2))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="siteName">
            Der Name der app.
            </param>
        <param name="filter">
            Filter wird mithilfe von OData-Syntax angegeben. Beispiel: $filter = Kanäle Eq "-Api" oder den Kanal Eq "Benachrichtigung" und "StartTime" Eq "2014-01-01T00:00:00Z" und EndTime-Eq "2014-12-31T23:59:59Z" und die Dauer der timegrain-Wert-Eq "[PT1H | PT1M | P1D]
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Darüber hinaus Empfehlungen für eine app, die optional angegeben werden, indem Sie den Zeitbereich.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Darüber hinaus Empfehlungen für eine app, die optional angegeben werden, indem Sie den Zeitbereich.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRecommendedRulesForWebAppAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt; ListRecommendedRulesForWebAppAsync (this Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations operations, string resourceGroupName, string siteName, Nullable&lt;bool&gt; featured = null, string filter = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt; ListRecommendedRulesForWebAppAsync(class Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations operations, string resourceGroupName, string siteName, valuetype System.Nullable`1&lt;bool&gt; featured, string filter, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions.ListRecommendedRulesForWebAppAsync(Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations,System.String,System.String,System.Nullable{System.Boolean},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListRecommendedRulesForWebAppAsync : Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations * string * string * Nullable&lt;bool&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions.ListRecommendedRulesForWebAppAsync (operations, resourceGroupName, siteName, featured, filter, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions/&lt;ListRecommendedRulesForWebAppAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.Management.AppService.Fluent.Models.RecommendationInner&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="featured" Type="System.Nullable&lt;System.Boolean&gt;" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="siteName">
            Der Name der app.
            </param>
        <param name="featured">
            Geben Sie &lt;Code&gt;"true"&lt;/code&gt; nur die wichtigsten Empfehlungen zurückgegeben. Die Standardeinstellung ist &lt;Code&gt;"false"&lt;/code&gt;, wobei alle Empfehlungen zurückgegeben.
            </param>
        <param name="filter">
            Geben Sie nur die Kanäle, die im Filter angegebenen zurück. Filter wird mithilfe von OData-Syntax angegeben. Beispiel: $filter = Kanäle Eq "-Api" oder den Kanal Eq "Benachrichtigung"
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Rufen Sie aller Empfehlungen für eine app an ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Rufen Sie aller Empfehlungen für eine app an ab.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetAllFiltersAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ResetAllFiltersAsync (this Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ResetAllFiltersAsync(class Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions.ResetAllFiltersAsync(Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResetAllFiltersAsync : Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions.ResetAllFiltersAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions/&lt;ResetAllFiltersAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations" RefType="this" />
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
            Setzen Sie alle Empfehlung opt-Out-Einstellungen für ein Abonnement zurück.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Setzen Sie alle Empfehlung opt-Out-Einstellungen für ein Abonnement zurück.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetAllFiltersForWebAppAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ResetAllFiltersForWebAppAsync (this Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations operations, string resourceGroupName, string siteName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ResetAllFiltersForWebAppAsync(class Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations operations, string resourceGroupName, string siteName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions.ResetAllFiltersForWebAppAsync(Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ResetAllFiltersForWebAppAsync : Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions.ResetAllFiltersForWebAppAsync (operations, resourceGroupName, siteName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.AppService.Fluent.RecommendationsOperationsExtensions/&lt;ResetAllFiltersForWebAppAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.AppService.Fluent.IRecommendationsOperations" RefType="this" />
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="siteName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceGroupName">
            Der Name der Ressourcengruppe, zu der die Ressource gehört.
            </param>
        <param name="siteName">
            Der Name der app.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Alle Empfehlung opt-Out-Einstellungen für eine app zurücksetzen.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            Alle Empfehlung opt-Out-Einstellungen für eine app zurücksetzen.
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>