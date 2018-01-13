<Type Name="UsageDetailsOperationsExtensions" FullName="Microsoft.Azure.Management.Consumption.UsageDetailsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class UsageDetailsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit UsageDetailsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Consumption.UsageDetailsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module UsageDetailsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type UsageDetailsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Erweiterungsmethoden für UsageDetailsOperations.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt; List (this Microsoft.Azure.Management.Consumption.IUsageDetailsOperations operations, string scope, string expand = null, string filter = null, string skiptoken = null, Nullable&lt;int&gt; top = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt; List(class Microsoft.Azure.Management.Consumption.IUsageDetailsOperations operations, string scope, string expand, string filter, string skiptoken, valuetype System.Nullable`1&lt;int32&gt; top) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Consumption.UsageDetailsOperationsExtensions.List(Microsoft.Azure.Management.Consumption.IUsageDetailsOperations,System.String,System.String,System.String,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IUsageDetailsOperations, scope As String, Optional expand As String = null, Optional filter As String = null, Optional skiptoken As String = null, Optional top As Nullable(Of Integer) = null) As IPage(Of UsageDetail)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Consumption.IUsageDetailsOperations * string * string * string * string * Nullable&lt;int&gt; -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;" Usage="Microsoft.Azure.Management.Consumption.UsageDetailsOperationsExtensions.List (operations, scope, expand, filter, skiptoken, top)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Consumption.IUsageDetailsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="skiptoken" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="scope">
            Der Bereich die Verwendungsdetails. Der Bereich kann "/ Subscriptions / {SubscriptionId}" für ein Abonnement, oder "/ subscriptions/{subscriptionId}/providers/Microsoft.Billing/billingPeriods/{billingPeriodName}" für einen Abrechnungszyklus Perdiod.
            </param>
        <param name="expand">
            Kann verwendet werden, um die Eigenschaften / "AdditionalProperties" oder die Eigenschaften/MeterDetails in einer Liste von Nutzungsdetails zu erweitern. Standardmäßig sind diese Felder nicht eingeschlossen, wenn Nutzungsdetails aufgelistet.
            </param>
        <param name="filter">
            Kann verwendet werden UsageDetails Filtern von Eigenschaften/UsageEnd (Utc-Zeit), -Eigenschaften/UsageStart (Utc-Zeit), Eigenschaften / "ResourceGroup", Eigenschaften/InstanceName oder Eigenschaften/InstanceId. Der Filter unterstützt "Eq", "Lt", 'Gt', 'le', "ge", und "und". Es derzeit nicht unterstützt 'Ne', 'oder' oder 'nicht'.
            </param>
        <param name="skiptoken">
            Skiptoken wird nur verwendet, wenn der vorherige Vorgang ein Teilergebnis zurückgegeben.
            Wenn eine vorherige Antwort ein "NextLink"-Element enthält, wird der Wert des Elements "NextLink" einen Skiptoken-Parameter enthalten, der einen Ausgangspunkt für die Verwendung für nachfolgende Aufrufe zu angibt.
            </param>
        <param name="top">
            Kann verwendet werden, um die Anzahl der Ergebnisse in den letzten N UsageDetails zu beschränken.
            </param>
        <summary>
            Listet die Verwendungsdetails für einen Bereich von Abrechnungszeitraum. Nutzungsdetails sind nur über diese API nur für am 1. Mai 2014 oder höher verfügbar.
            <see href="https://docs.microsoft.com/en-us/azure/billing/billing-enterprise-api" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt; ListAsync (this Microsoft.Azure.Management.Consumption.IUsageDetailsOperations operations, string scope, string expand = null, string filter = null, string skiptoken = null, Nullable&lt;int&gt; top = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt; ListAsync(class Microsoft.Azure.Management.Consumption.IUsageDetailsOperations operations, string scope, string expand, string filter, string skiptoken, valuetype System.Nullable`1&lt;int32&gt; top, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Consumption.UsageDetailsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Consumption.IUsageDetailsOperations,System.String,System.String,System.String,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Consumption.IUsageDetailsOperations * string * string * string * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;" Usage="Microsoft.Azure.Management.Consumption.UsageDetailsOperationsExtensions.ListAsync (operations, scope, expand, filter, skiptoken, top, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Consumption.UsageDetailsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Consumption.IUsageDetailsOperations" RefType="this" />
        <Parameter Name="scope" Type="System.String" />
        <Parameter Name="expand" Type="System.String" />
        <Parameter Name="filter" Type="System.String" />
        <Parameter Name="skiptoken" Type="System.String" />
        <Parameter Name="top" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            Die Operations-Gruppe für diese Erweiterungsmethode.
            </param>
        <param name="scope">
            Der Bereich die Verwendungsdetails. Der Bereich kann "/ Subscriptions / {SubscriptionId}" für ein Abonnement, oder "/ subscriptions/{subscriptionId}/providers/Microsoft.Billing/billingPeriods/{billingPeriodName}" für einen Abrechnungszyklus Perdiod.
            </param>
        <param name="expand">
            Kann verwendet werden, um die Eigenschaften / "AdditionalProperties" oder die Eigenschaften/MeterDetails in einer Liste von Nutzungsdetails zu erweitern. Standardmäßig sind diese Felder nicht eingeschlossen, wenn Nutzungsdetails aufgelistet.
            </param>
        <param name="filter">
            Kann verwendet werden UsageDetails Filtern von Eigenschaften/UsageEnd (Utc-Zeit), -Eigenschaften/UsageStart (Utc-Zeit), Eigenschaften / "ResourceGroup", Eigenschaften/InstanceName oder Eigenschaften/InstanceId. Der Filter unterstützt "Eq", "Lt", 'Gt', 'le', "ge", und "und". Es derzeit nicht unterstützt 'Ne', 'oder' oder 'nicht'.
            </param>
        <param name="skiptoken">
            Skiptoken wird nur verwendet, wenn der vorherige Vorgang ein Teilergebnis zurückgegeben.
            Wenn eine vorherige Antwort ein "NextLink"-Element enthält, wird der Wert des Elements "NextLink" einen Skiptoken-Parameter enthalten, der einen Ausgangspunkt für die Verwendung für nachfolgende Aufrufe zu angibt.
            </param>
        <param name="top">
            Kann verwendet werden, um die Anzahl der Ergebnisse in den letzten N UsageDetails zu beschränken.
            </param>
        <param name="cancellationToken">
            Das Abbruchtoken.
            </param>
        <summary>
            Listet die Verwendungsdetails für einen Bereich von Abrechnungszeitraum. Nutzungsdetails sind nur über diese API nur für am 1. Mai 2014 oder höher verfügbar.
            <see href="https://docs.microsoft.com/en-us/azure/billing/billing-enterprise-api" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNext">
      <MemberSignature Language="C#" Value="public static Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt; ListNext (this Microsoft.Azure.Management.Consumption.IUsageDetailsOperations operations, string nextPageLink);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt; ListNext(class Microsoft.Azure.Management.Consumption.IUsageDetailsOperations operations, string nextPageLink) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Consumption.UsageDetailsOperationsExtensions.ListNext(Microsoft.Azure.Management.Consumption.IUsageDetailsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function ListNext (operations As IUsageDetailsOperations, nextPageLink As String) As IPage(Of UsageDetail)" />
      <MemberSignature Language="F#" Value="static member ListNext : Microsoft.Azure.Management.Consumption.IUsageDetailsOperations * string -&gt; Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;" Usage="Microsoft.Azure.Management.Consumption.UsageDetailsOperationsExtensions.ListNext (operations, nextPageLink)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Consumption.IUsageDetailsOperations" RefType="this" />
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
            Listet die Verwendungsdetails für einen Bereich von Abrechnungszeitraum. Nutzungsdetails sind nur über diese API nur für am 1. Mai 2014 oder höher verfügbar.
            <see href="https://docs.microsoft.com/en-us/azure/billing/billing-enterprise-api" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListNextAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt; ListNextAsync (this Microsoft.Azure.Management.Consumption.IUsageDetailsOperations operations, string nextPageLink, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt; ListNextAsync(class Microsoft.Azure.Management.Consumption.IUsageDetailsOperations operations, string nextPageLink, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Consumption.UsageDetailsOperationsExtensions.ListNextAsync(Microsoft.Azure.Management.Consumption.IUsageDetailsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListNextAsync : Microsoft.Azure.Management.Consumption.IUsageDetailsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;" Usage="Microsoft.Azure.Management.Consumption.UsageDetailsOperationsExtensions.ListNextAsync (operations, nextPageLink, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Consumption</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Consumption.UsageDetailsOperationsExtensions/&lt;ListNextAsync&gt;d__3))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Consumption.Models.UsageDetail&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Consumption.IUsageDetailsOperations" RefType="this" />
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
            Listet die Verwendungsdetails für einen Bereich von Abrechnungszeitraum. Nutzungsdetails sind nur über diese API nur für am 1. Mai 2014 oder höher verfügbar.
            <see href="https://docs.microsoft.com/en-us/azure/billing/billing-enterprise-api" /></summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>