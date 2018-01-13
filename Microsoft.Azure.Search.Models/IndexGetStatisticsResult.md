<Type Name="IndexGetStatisticsResult" FullName="Microsoft.Azure.Search.Models.IndexGetStatisticsResult">
  <TypeSignature Language="C#" Value="public class IndexGetStatisticsResult" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit IndexGetStatisticsResult extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Search.Models.IndexGetStatisticsResult" />
  <TypeSignature Language="VB.NET" Value="Public Class IndexGetStatisticsResult" />
  <TypeSignature Language="F#" Value="type IndexGetStatisticsResult = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Search</AssemblyName>
    <AssemblyVersion>3.0.0.0</AssemblyVersion>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Statistiken für einen bestimmten Index. Statistiken wurden in regelmäßigen Abständen erfasst und sind nicht unbedingt immer auf dem neuesten Stand.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexGetStatisticsResult ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexGetStatisticsResult.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der IndexGetStatisticsResult-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public IndexGetStatisticsResult (long documentCount = 0, long storageSize = 0);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(int64 documentCount, int64 storageSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Search.Models.IndexGetStatisticsResult.#ctor(System.Int64,System.Int64)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (Optional documentCount As Long = 0, Optional storageSize As Long = 0)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Search.Models.IndexGetStatisticsResult : int64 * int64 -&gt; Microsoft.Azure.Search.Models.IndexGetStatisticsResult" Usage="new Microsoft.Azure.Search.Models.IndexGetStatisticsResult (documentCount, storageSize)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="documentCount" Type="System.Int64" />
        <Parameter Name="storageSize" Type="System.Int64" />
      </Parameters>
      <Docs>
        <param name="documentCount">Die Anzahl der Dokumente im Index.</param>
        <param name="storageSize">Die Menge des Speichers in Bytes, die vom Index belegt.</param>
        <summary>
            Initialisiert eine neue Instanz der IndexGetStatisticsResult-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DocumentCount">
      <MemberSignature Language="C#" Value="public long DocumentCount { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 DocumentCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexGetStatisticsResult.DocumentCount" />
      <MemberSignature Language="VB.NET" Value="Public Property DocumentCount As Long" />
      <MemberSignature Language="F#" Value="member this.DocumentCount : int64 with get, set" Usage="Microsoft.Azure.Search.Models.IndexGetStatisticsResult.DocumentCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="documentCount")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzahl der Dokumente im Index.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageSize">
      <MemberSignature Language="C#" Value="public long StorageSize { get; protected set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 StorageSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Search.Models.IndexGetStatisticsResult.StorageSize" />
      <MemberSignature Language="VB.NET" Value="Public Property StorageSize As Long" />
      <MemberSignature Language="F#" Value="member this.StorageSize : int64 with get, set" Usage="Microsoft.Azure.Search.Models.IndexGetStatisticsResult.StorageSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Search</AssemblyName>
        <AssemblyVersion>3.0.0.0</AssemblyVersion>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Newtonsoft.Json.JsonProperty(PropertyName="storageSize")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Menge des Speichers in Bytes, belegt werden durch den Index ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>