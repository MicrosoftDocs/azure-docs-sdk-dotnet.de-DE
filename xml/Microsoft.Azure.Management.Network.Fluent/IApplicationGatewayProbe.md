<Type Name="IApplicationGatewayProbe" FullName="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayProbe">
  <TypeSignature Language="C#" Value="public interface IApplicationGatewayProbe : Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayProbeBeta, Microsoft.Azure.Management.Network.Fluent.IHasProtocol&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayProtocol&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayProbeInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IApplicationGatewayProbe implements class Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayProbeBeta, class Microsoft.Azure.Management.Network.Fluent.IHasProtocol`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayProtocol&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayProbeInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayProbe" />
  <TypeSignature Language="VB.NET" Value="Public Interface IApplicationGatewayProbe&#xA;Implements IApplicationGatewayProbeBeta, IBeta, IChildResource(Of IApplicationGateway), IHasInner(Of ApplicationGatewayProbeInner), IHasParent(Of IApplicationGateway), IHasProtocol(Of ApplicationGatewayProtocol)" />
  <TypeSignature Language="F#" Value="type IApplicationGatewayProbe = interface&#xA;    interface IHasInner&lt;ApplicationGatewayProbeInner&gt;&#xA;    interface IChildResource&lt;IApplicationGateway&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;IApplicationGateway&gt;&#xA;    interface IHasProtocol&lt;ApplicationGatewayProtocol&gt;&#xA;    interface IApplicationGatewayProbeBeta&#xA;    interface IBeta" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayProbeBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.IHasProtocol&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayProtocol&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayProbeInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.IApplicationGateway&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="301e8-101">Eine unveränderliche clientseitige Darstellung von einer Anwendung Gateway-Prüfpunkt.</span><span class="sxs-lookup"><span data-stu-id="301e8-101">An immutable client-side representation of an application gateway probe.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="301e8-102">(Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).</span><span class="sxs-lookup"><span data-stu-id="301e8-102">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="Host">
      <MemberSignature Language="C#" Value="public string Host { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Host" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayProbe.Host" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Host As String" />
      <MemberSignature Language="F#" Value="member this.Host : string" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayProbe.Host" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="301e8-103">Ruft ab, Hostname, der die Überprüfung zu senden.</span><span class="sxs-lookup"><span data-stu-id="301e8-103">Gets host name to send the probe to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Path">
      <MemberSignature Language="C#" Value="public string Path { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Path" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayProbe.Path" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Path As String" />
      <MemberSignature Language="F#" Value="member this.Path : string" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayProbe.Path" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="301e8-104">Ruft den relativen Pfad zum nach der Überprüfung aufgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="301e8-104">Gets the relative path to be called by the probe.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetriesBeforeUnhealthy">
      <MemberSignature Language="C#" Value="public int RetriesBeforeUnhealthy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 RetriesBeforeUnhealthy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayProbe.RetriesBeforeUnhealthy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RetriesBeforeUnhealthy As Integer" />
      <MemberSignature Language="F#" Value="member this.RetriesBeforeUnhealthy : int" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayProbe.RetriesBeforeUnhealthy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="301e8-105">Ruft die Anzahl der fehlgeschlagenen Tests vor der Back-End-Server markiert ist, ausgefallen zulässigen Werte von 1 Sekunde auf 20 sind.</span><span class="sxs-lookup"><span data-stu-id="301e8-105">Gets the number of failed retry probes before the backend server is marked as being down Acceptable values are from 1 second to 20.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeBetweenProbesInSeconds">
      <MemberSignature Language="C#" Value="public int TimeBetweenProbesInSeconds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 TimeBetweenProbesInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayProbe.TimeBetweenProbesInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TimeBetweenProbesInSeconds As Integer" />
      <MemberSignature Language="F#" Value="member this.TimeBetweenProbesInSeconds : int" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayProbe.TimeBetweenProbesInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="301e8-106">Ruft die Anzahl der Sekunden zwischen den Prüfpunkt Wiederholungen ab.</span><span class="sxs-lookup"><span data-stu-id="301e8-106">Gets the number of seconds between probe retries.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeoutInSeconds">
      <MemberSignature Language="C#" Value="public int TimeoutInSeconds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 TimeoutInSeconds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayProbe.TimeoutInSeconds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TimeoutInSeconds As Integer" />
      <MemberSignature Language="F#" Value="member this.TimeoutInSeconds : int" Usage="Microsoft.Azure.Management.Network.Fluent.IApplicationGatewayProbe.TimeoutInSeconds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="301e8-107">Ruft die Anzahl der Sekunden warten auf Antwort nach dem der Test ein Timeout auftritt, und es als fehlerhaften zulässigen Werte von 1 auf 86400 Sekunden sind gekennzeichnet.</span><span class="sxs-lookup"><span data-stu-id="301e8-107">Gets the number of seconds waiting for a response after which the probe times out and it is marked as failed Acceptable values are from 1 to 86400 seconds.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>