<Type Name="ChangeFeedHostOptions" FullName="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions">
  <TypeSignature Language="C#" Value="public class ChangeFeedHostOptions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit ChangeFeedHostOptions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions" />
  <TypeSignature Language="VB.NET" Value="Public Class ChangeFeedHostOptions" />
  <TypeSignature Language="F#" Value="type ChangeFeedHostOptions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.17.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Optionen zum Steuern der verschiedene Aspekte der Partition Verteilung im <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" /> Instanz.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public ChangeFeedHostOptions ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions" />-Klasse.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CheckpointFrequency">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Documents.ChangeFeedProcessor.CheckpointFrequency CheckpointFrequency { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Documents.ChangeFeedProcessor.CheckpointFrequency CheckpointFrequency" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.CheckpointFrequency" />
      <MemberSignature Language="VB.NET" Value="Public Property CheckpointFrequency As CheckpointFrequency" />
      <MemberSignature Language="F#" Value="member this.CheckpointFrequency : Microsoft.Azure.Documents.ChangeFeedProcessor.CheckpointFrequency with get, set" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.CheckpointFrequency" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Documents.ChangeFeedProcessor.CheckpointFrequency</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die die Häufigkeit, wie oft die Prüfpunkt-Leases.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FeedPollDelay">
      <MemberSignature Language="C#" Value="public TimeSpan FeedPollDelay { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan FeedPollDelay" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.FeedPollDelay" />
      <MemberSignature Language="VB.NET" Value="Public Property FeedPollDelay As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.FeedPollDelay : TimeSpan with get, set" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.FeedPollDelay" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Verzögerung zwischen den Abruf eine Partition neue Änderungen auf den feed, nachdem alle aktuellen Änderungen entladen werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseAcquireInterval">
      <MemberSignature Language="C#" Value="public TimeSpan LeaseAcquireInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LeaseAcquireInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.LeaseAcquireInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property LeaseAcquireInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LeaseAcquireInterval : TimeSpan with get, set" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.LeaseAcquireInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Zeitintervall fest, starten Sie eine Aufgabe berechnet wird, wenn Sie Partitionen auf bekannte Hostinstanzen gleichmäßig verteilt sind. 
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseExpirationInterval">
      <MemberSignature Language="C#" Value="public TimeSpan LeaseExpirationInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LeaseExpirationInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.LeaseExpirationInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property LeaseExpirationInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LeaseExpirationInterval : TimeSpan with get, set" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.LeaseExpirationInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Intervall für das die Lease für eine Lease, eine Partition darstellt, ausgeführt wird. Wenn die Lease innerhalb dieses Zeitraums nicht erneuert wird, bewirkt ablaufen und den Besitz der Partition wird in einen anderen verschieben <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" /> Instanz.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeasePrefix">
      <MemberSignature Language="C#" Value="public string LeasePrefix { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LeasePrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.LeasePrefix" />
      <MemberSignature Language="VB.NET" Value="Public Property LeasePrefix As String" />
      <MemberSignature Language="F#" Value="member this.LeasePrefix : string with get, set" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.LeasePrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ermittelt oder definiert ein Präfix, das als Teil der Lease-Id verwendet werden. Dies kann verwendet werden, um mehrere unterstützen <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" /> Instanzen desselben Feeds im bei der Verwendung von zusätzlichen derselben Sammlung auf.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LeaseRenewInterval">
      <MemberSignature Language="C#" Value="public TimeSpan LeaseRenewInterval { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan LeaseRenewInterval" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.LeaseRenewInterval" />
      <MemberSignature Language="VB.NET" Value="Public Property LeaseRenewInterval As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.LeaseRenewInterval : TimeSpan with get, set" Usage="Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedHostOptions.LeaseRenewInterval" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.ChangeFeedProcessor</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.17.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt Erneuerungsintervall für alle Leases für Partitionen, die derzeit von reservierten <see cref="T:Microsoft.Azure.Documents.ChangeFeedProcessor.ChangeFeedEventHost" /> Instanz.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>