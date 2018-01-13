<Type Name="ProvidersOperationsExtensions" FullName="Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class ProvidersOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit ProvidersOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module ProvidersOperationsExtensions" />
  <TypeSignature Language="F#" Value="type ProvidersOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für ProvidersOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Get">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.Provider Get (this Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string resourceProviderNamespace, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.Provider Get(class Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string resourceProviderNamespace, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.Get(Microsoft.Azure.Management.ResourceManager.IProvidersOperations,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Get (operations As IProvidersOperations, resourceProviderNamespace As String, Optional expand As String = null) As Provider" />
      <MemberSignature Language="F#" Value="static member Get : Microsoft.Azure.Management.ResourceManager.IProvidersOperations * string * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.Provider" Usage="Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.Get (operations, resourceProviderNamespace, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.Provider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IProvidersOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceProviderNamespace">
            Der Namespace des Ressourcenanbieters.
            </param>
        <param name="expand">
            Die $expand-Abfrageparameter. Angenommen, für die Einbeziehung der Eigenschaft Aliase in der Antwort verwenden $expand-= Ressourcentypen/Aliase.
            </param>
        <summary>
            Ruft die angegebene Ressourcenanbieter ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt; GetAsync (this Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string resourceProviderNamespace, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.Provider&gt; GetAsync(class Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string resourceProviderNamespace, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.GetAsync(Microsoft.Azure.Management.ResourceManager.IProvidersOperations,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetAsync : Microsoft.Azure.Management.ResourceManager.IProvidersOperations * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.GetAsync (operations, resourceProviderNamespace, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions/&lt;GetAsync&gt;d__7))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IProvidersOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceProviderNamespace">
            Der Namespace des Ressourcenanbieters.
            </param>
        <param name="expand">
            Die $expand-Abfrageparameter. Angenommen, für die Einbeziehung der Eigenschaft Aliase in der Antwort verwenden $expand-= Ressourcentypen/Aliase.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft die angegebene Ressourcenanbieter ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt; List (this Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, Nullable&lt;int&gt; top = null, string expand = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.Provider&gt; List(class Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, valuetype System.Nullable`1&lt;int32&gt; top, string expand) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.List(Microsoft.Azure.Management.ResourceManager.IProvidersOperations,System.Nullable{System.Int32},System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IProvidersOperations, Optional top As Nullable(Of Integer) = null, Optional expand As String = null) As IPage(Of Provider)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.ResourceManager.IProvidersOperations * Nullable&lt;int&gt; * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.List (operations, top, expand)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IProvidersOperations" RefType="this" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="expand" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="top">
            Die Anzahl der zurückzugebenden Ergebnisseite. Werden alle Bereitstellungen angegeben, wenn Null übergeben wird.
            </param>
        <param name="expand">
            Die Eigenschaften in die Ergebnisse eingeschlossen werden sollen. Verwenden Sie z. B. &amp;$expand-= Metadaten in der Abfragezeichenfolge zum Abrufen von Anbietermetadaten Ressource. Für die Einbeziehung der Eigenschaft Aliase in der Antwort verwenden $expand-= Ressourcentypen/Aliase.
            </param>
        <summary>
            Ruft alle Ressourcenanbieter für ein Abonnement ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;&gt; ListAsync (this Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, Nullable&lt;int&gt; top = null, string expand = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;&gt; ListAsync(class Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, valuetype System.Nullable`1&lt;int32&gt; top, string expand, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.ListAsync(Microsoft.Azure.Management.ResourceManager.IProvidersOperations,System.Nullable{System.Int32},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.ResourceManager.IProvidersOperations * Nullable&lt;int&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.ListAsync (operations, top, expand, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions/&lt;ListAsync&gt;d__5))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IProvidersOperations" RefType="this" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="top">
            Die Anzahl der zurückzugebenden Ergebnisseite. Werden alle Bereitstellungen angegeben, wenn Null übergeben wird.
            </param>
        <param name="expand">
            Die Eigenschaften in die Ergebnisse eingeschlossen werden sollen. Verwenden Sie z. B. &amp;$expand-= Metadaten in der Abfragezeichenfolge zum Abrufen von Anbietermetadaten Ressource. Für die Einbeziehung der Eigenschaft Aliase in der Antwort verwenden $expand-= Ressourcentypen/Aliase.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft alle Ressourcenanbieter für ein Abonnement ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt; ListNext (this Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.Provider&gt; ListNext(class Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.ListNext(Microsoft.Azure.Management.ResourceManager.IProvidersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IProvidersOperations, nextPageLink As String) As IPage(Of Provider)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.ResourceManager.IProvidersOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IProvidersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <summary>
            Ruft alle Ressourcenanbieter für ein Abonnement ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.ResourceManager.IProvidersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.ResourceManager.IProvidersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions/&lt;ListNextAsync&gt;d__9))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IProvidersOperations" RefType="this" />
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="nextPageLink">
            Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Ruft alle Ressourcenanbieter für ein Abonnement ab.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Register">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.Provider Register (this Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string resourceProviderNamespace);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.Provider Register(class Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string resourceProviderNamespace) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.Register(Microsoft.Azure.Management.ResourceManager.IProvidersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Register (operations As IProvidersOperations, resourceProviderNamespace As String) As Provider" />
      <MemberSignature Language="F#" Value="static member Register : Microsoft.Azure.Management.ResourceManager.IProvidersOperations * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.Provider" Usage="Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.Register (operations, resourceProviderNamespace)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.Provider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IProvidersOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceProviderNamespace">
            Der Namespace des Ressourcenanbieters registrieren.
            </param>
        <summary>
            Registriert ein Abonnement mit einem Ressourcenanbieter an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegisterAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt; RegisterAsync (this Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string resourceProviderNamespace, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.Provider&gt; RegisterAsync(class Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string resourceProviderNamespace, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.RegisterAsync(Microsoft.Azure.Management.ResourceManager.IProvidersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member RegisterAsync : Microsoft.Azure.Management.ResourceManager.IProvidersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.RegisterAsync (operations, resourceProviderNamespace, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions/&lt;RegisterAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IProvidersOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceProviderNamespace">
            Der Namespace des Ressourcenanbieters registrieren.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Registriert ein Abonnement mit einem Ressourcenanbieter an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Unregister">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.ResourceManager.Models.Provider Unregister (this Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string resourceProviderNamespace);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.ResourceManager.Models.Provider Unregister(class Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string resourceProviderNamespace) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.Unregister(Microsoft.Azure.Management.ResourceManager.IProvidersOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function Unregister (operations As IProvidersOperations, resourceProviderNamespace As String) As Provider" />
      <MemberSignature Language="F#" Value="static member Unregister : Microsoft.Azure.Management.ResourceManager.IProvidersOperations * string -&gt; Microsoft.Azure.Management.ResourceManager.Models.Provider" Usage="Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.Unregister (operations, resourceProviderNamespace)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Models.Provider</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IProvidersOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceProviderNamespace">
            Der Namespace des Ressourcenanbieters aufgehoben werden.
            </param>
        <summary>
            Hebt die Registrierung eines Abonnements von einem Ressourcenanbieter.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UnregisterAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt; UnregisterAsync (this Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string resourceProviderNamespace, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.ResourceManager.Models.Provider&gt; UnregisterAsync(class Microsoft.Azure.Management.ResourceManager.IProvidersOperations operations, string resourceProviderNamespace, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.UnregisterAsync(Microsoft.Azure.Management.ResourceManager.IProvidersOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member UnregisterAsync : Microsoft.Azure.Management.ResourceManager.IProvidersOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;" Usage="Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions.UnregisterAsync (operations, resourceProviderNamespace, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.ResourceManager.ProvidersOperationsExtensions/&lt;UnregisterAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.ResourceManager.Models.Provider&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.ResourceManager.IProvidersOperations" RefType="this" />
        <Parameter Name="resourceProviderNamespace" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="resourceProviderNamespace">
            Der Namespace des Ressourcenanbieters aufgehoben werden.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Hebt die Registrierung eines Abonnements von einem Ressourcenanbieter.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>