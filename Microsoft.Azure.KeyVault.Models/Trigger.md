<Type Name="Trigger" FullName="Microsoft.Azure.KeyVault.Models.Trigger">
  <TypeSignature Language="C#" Value="public class Trigger" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit Trigger extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.Models.Trigger" />
  <TypeSignature Language="VB.NET" Value="Public Class Trigger" />
  <TypeSignature Language="F#" Value="type Trigger = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Eine Bedingung, die für eine Aktion ausgeführt werden, erfüllt werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Trigger ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.Trigger.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der betreffenden auslöserklasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public Trigger (Nullable&lt;int&gt; lifetimePercentage = null, Nullable&lt;int&gt; daysBeforeExpiry = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype System.Nullable`1&lt;int32&gt; lifetimePercentage, valuetype System.Nullable`1&lt;int32&gt; daysBeforeExpiry) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.Trigger.#ctor(System.Nullable{System.Int32},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional lifetimePercentage As Nullable(Of Integer) = null, Optional daysBeforeExpiry As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.KeyVault.Models.Trigger : Nullable&lt;int&gt; * Nullable&lt;int&gt; -&gt; Microsoft.Azure.KeyVault.Models.Trigger" Usage="new Microsoft.Azure.KeyVault.Models.Trigger (lifetimePercentage, daysBeforeExpiry)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="lifetimePercentage" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="daysBeforeExpiry" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="lifetimePercentage">Prozentsatz der Lebensdauer, auf denen ausgelöst. Wert muss zwischen 1 und 99 liegen.</param>
        <param name="daysBeforeExpiry">Tage bis zum Ablauf.</param>
        <summary>
            Initialisiert eine neue Instanz der betreffenden auslöserklasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DaysBeforeExpiry">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; DaysBeforeExpiry { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; DaysBeforeExpiry" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.Trigger.DaysBeforeExpiry" />
      <MemberSignature Language="VB.NET" Value="Public Property DaysBeforeExpiry As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.DaysBeforeExpiry : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.Trigger.DaysBeforeExpiry" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="days_before_expiry")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder Tage vor Ablauf festgelegt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LifetimePercentage">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; LifetimePercentage { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; LifetimePercentage" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.KeyVault.Models.Trigger.LifetimePercentage" />
      <MemberSignature Language="VB.NET" Value="Public Property LifetimePercentage As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.LifetimePercentage : Nullable&lt;int&gt; with get, set" Usage="Microsoft.Azure.KeyVault.Models.Trigger.LifetimePercentage" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="lifetime_percentage")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Abrufen oder Festlegen der Prozentsatz der Lebensdauer, auf denen ausgelöst. Wert muss zwischen 1 und 99 liegen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.Models.Trigger.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="trigger.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Überprüfen Sie das Objekt.
            </summary>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.ValidationException">
            Wird ausgelöst, wenn die Validierung fehlschlägt
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>