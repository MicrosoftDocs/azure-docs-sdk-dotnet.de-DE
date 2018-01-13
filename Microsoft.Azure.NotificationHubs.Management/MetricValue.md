<Type Name="MetricValue" FullName="Microsoft.Azure.NotificationHubs.Management.MetricValue">
  <TypeSignature Language="C#" Value="public class MetricValue" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit MetricValue extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.NotificationHubs.Management.MetricValue" />
  <TypeSignature Language="VB.NET" Value="Public Class MetricValue" />
  <TypeSignature Language="F#" Value="type MetricValue = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
    <AssemblyVersion>2.16.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>Stellt den Wert einer Metrik Servicebus zugeordnet.</summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public MetricValue ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.NotificationHubs.Management.MetricValue.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.NotificationHubs.Management.MetricValue" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Average">
      <MemberSignature Language="C#" Value="public float Average { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance float32 Average" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.MetricValue.Average" />
      <MemberSignature Language="VB.NET" Value="Public Property Average As Single" />
      <MemberSignature Language="F#" Value="member this.Average : single with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.MetricValue.Average" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Single</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Durchschnittswert einer Metrik.</summary>
        <value>Der Durchschnittswert der Metrik.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Max">
      <MemberSignature Language="C#" Value="public long Max { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Max" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.MetricValue.Max" />
      <MemberSignature Language="VB.NET" Value="Public Property Max As Long" />
      <MemberSignature Language="F#" Value="member this.Max : int64 with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.MetricValue.Max" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den maximalen Wert einer Metrik.</summary>
        <value>Der maximale Wert einer Metrik.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Min">
      <MemberSignature Language="C#" Value="public long Min { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Min" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.MetricValue.Min" />
      <MemberSignature Language="VB.NET" Value="Public Property Min As Long" />
      <MemberSignature Language="F#" Value="member this.Min : int64 with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.MetricValue.Min" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den minimalen Wert einer Metrik.</summary>
        <value>Der kleinste Wert einer Metrik.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timestamp">
      <MemberSignature Language="C#" Value="public DateTime Timestamp { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime Timestamp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.MetricValue.Timestamp" />
      <MemberSignature Language="VB.NET" Value="Public Property Timestamp As DateTime" />
      <MemberSignature Language="F#" Value="member this.Timestamp : DateTime with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.MetricValue.Timestamp" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.ComponentModel.DataAnnotations.Key</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab oder legt den Zeitstempel der Metrikwert zugeordnet.</summary>
        <value>Der Zeitstempel der Metrikwert zugeordnet.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Total">
      <MemberSignature Language="C#" Value="public long Total { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 Total" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.NotificationHubs.Management.MetricValue.Total" />
      <MemberSignature Language="VB.NET" Value="Public Property Total As Long" />
      <MemberSignature Language="F#" Value="member this.Total : int64 with get, set" Usage="Microsoft.Azure.NotificationHubs.Management.MetricValue.Total" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.NotificationHubs</AssemblyName>
        <AssemblyVersion>2.16.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>Ruft ab, oder legt ihn fest den Gesamtwert der Metriken.</summary>
        <value>Der Metrik Gesamtwert.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>