<Type Name="SubscriptionPolicies" FullName="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies">
  <TypeSignature Language="C#" Value="public class SubscriptionPolicies" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit SubscriptionPolicies extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies" />
  <TypeSignature Language="VB.NET" Value="Public Class SubscriptionPolicies" />
  <TypeSignature Language="F#" Value="type SubscriptionPolicies = class" />
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
            Abonnement-Richtlinien.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubscriptionPolicies ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der SubscriptionPolicies-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public SubscriptionPolicies (string locationPlacementId = null, string quotaId = null, Nullable&lt;Microsoft.Azure.Management.ResourceManager.Models.SpendingLimit&gt; spendingLimit = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(string locationPlacementId, string quotaId, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ResourceManager.Models.SpendingLimit&gt; spendingLimit) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies.#ctor(System.String,System.String,System.Nullable{Microsoft.Azure.Management.ResourceManager.Models.SpendingLimit})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional locationPlacementId As String = null, Optional quotaId As String = null, Optional spendingLimit As Nullable(Of SpendingLimit) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies : string * string * Nullable&lt;Microsoft.Azure.Management.ResourceManager.Models.SpendingLimit&gt; -&gt; Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies" Usage="new Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies (locationPlacementId, quotaId, spendingLimit)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="locationPlacementId" Type="System.String" />
        <Parameter Name="quotaId" Type="System.String" />
        <Parameter Name="spendingLimit" Type="System.Nullable&lt;Microsoft.Azure.Management.ResourceManager.Models.SpendingLimit&gt;" />
      </Parameters>
      <Docs>
        <param name="locationPlacementId">Die Abonnement-Speicherort-Platzierung-ID. Die ID gibt an, welche Regionen für das Abonnement sichtbar sind. Beispielsweise hat ein Abonnement mit einem Speicherort Platzierung Id des Public_2014-09-01 Zugriff auf Öffentliche Azure-Regionen.</param>
        <param name="quotaId">Die Abonnement-Kontingent-ID.</param>
        <param name="spendingLimit">Das Ausgabenlimit des Abonnements.
            Folgende Werte sind möglich: "On", "Off", "CurrentPeriodOff"</param>
        <summary>
            Initialisiert eine neue Instanz der SubscriptionPolicies-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LocationPlacementId">
      <MemberSignature Language="C#" Value="public string LocationPlacementId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LocationPlacementId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies.LocationPlacementId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LocationPlacementId As String" />
      <MemberSignature Language="F#" Value="member this.LocationPlacementId : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies.LocationPlacementId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="locationPlacementId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Abonnement-Speicherort-Platzierung-ID. Die ID gibt an, welche Regionen für das Abonnement sichtbar sind. Beispielsweise hat ein Abonnement mit einem Speicherort Platzierung Id des Public_2014-09-01 Zugriff auf Öffentliche Azure-Regionen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QuotaId">
      <MemberSignature Language="C#" Value="public string QuotaId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string QuotaId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies.QuotaId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property QuotaId As String" />
      <MemberSignature Language="F#" Value="member this.QuotaId : string" Usage="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies.QuotaId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="quotaId")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Abonnement-Kontingent-ID.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SpendingLimit">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.Management.ResourceManager.Models.SpendingLimit&gt; SpendingLimit { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Management.ResourceManager.Models.SpendingLimit&gt; SpendingLimit" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies.SpendingLimit" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SpendingLimit As Nullable(Of SpendingLimit)" />
      <MemberSignature Language="F#" Value="member this.SpendingLimit : Nullable&lt;Microsoft.Azure.Management.ResourceManager.Models.SpendingLimit&gt;" Usage="Microsoft.Azure.Management.ResourceManager.Models.SubscriptionPolicies.SpendingLimit" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ResourceManager</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="spendingLimit")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.Management.ResourceManager.Models.SpendingLimit&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Ausgabenlimit Abonnement ab. Folgende Werte sind möglich: "On", "Off", "CurrentPeriodOff"
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>