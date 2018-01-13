<Type Name="GrantAccessDataInner" FullName="Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner">
  <TypeSignature Language="C#" Value="public class GrantAccessDataInner" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit GrantAccessDataInner extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner" />
  <TypeSignature Language="VB.NET" Value="Public Class GrantAccessDataInner" />
  <TypeSignature Language="F#" Value="type GrantAccessDataInner = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Daten, die für die Anforderung eine SAS.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GrantAccessDataInner ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der GrantAccessDataInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public GrantAccessDataInner (Microsoft.Azure.Management.Compute.Fluent.Models.AccessLevel access, int durationInSeconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(valuetype Microsoft.Azure.Management.Compute.Fluent.Models.AccessLevel access, int32 durationInSeconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner.#ctor(Microsoft.Azure.Management.Compute.Fluent.Models.AccessLevel,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (access As AccessLevel, durationInSeconds As Integer)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner : Microsoft.Azure.Management.Compute.Fluent.Models.AccessLevel * int -&gt; Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner" Usage="new Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner (access, durationInSeconds)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="access" Type="Microsoft.Azure.Management.Compute.Fluent.Models.AccessLevel" />
        <Parameter Name="durationInSeconds" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="access">Folgende Werte sind möglich: 'None', 'Read'</param>
        <param name="durationInSeconds">Die Zeitdauer in Sekunden, bis der SAS-Zugriff läuft ab.</param>
        <summary>
            Initialisiert eine neue Instanz der GrantAccessDataInner-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Access">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.AccessLevel Access { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.AccessLevel Access" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner.Access" />
      <MemberSignature Language="VB.NET" Value="Public Property Access As AccessLevel" />
      <MemberSignature Language="F#" Value="member this.Access : Microsoft.Azure.Management.Compute.Fluent.Models.AccessLevel with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner.Access" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="access")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.AccessLevel</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt folgende Werte möglich sind: 'None', 'Read'
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DurationInSeconds">
      <MemberSignature Language="C#" Value="public int DurationInSeconds { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 DurationInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner.DurationInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public Property DurationInSeconds As Integer" />
      <MemberSignature Language="F#" Value="member this.DurationInSeconds : int with get, set" Usage="Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner.DurationInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="durationInSeconds")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Dauer in Sekunden bis zum Ablauf des SAS-Zugriffs fest.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Validate">
      <MemberSignature Language="C#" Value="public virtual void Validate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Validate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.Models.GrantAccessDataInner.Validate" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Validate ()" />
      <MemberSignature Language="F#" Value="abstract member Validate : unit -&gt; unit&#xA;override this.Validate : unit -&gt; unit" Usage="grantAccessDataInner.Validate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
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