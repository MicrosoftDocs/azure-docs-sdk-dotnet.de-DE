<Type Name="IWithTimeout" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IWithTimeout">
  <TypeSignature Language="C#" Value="public interface IWithTimeout" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithTimeout" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IWithTimeout" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithTimeout" />
  <TypeSignature Language="F#" Value="type IWithTimeout = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Phase ein Test der Anwendung Gateway aktualisieren, können angeben, dass die verstrichene Zeitspanne, nach der Prüfpunkts gilt fehlgeschlagen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithTimeoutInSeconds">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IUpdate WithTimeoutInSeconds (int seconds);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IUpdate WithTimeoutInSeconds(int32 seconds) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IWithTimeout.WithTimeoutInSeconds(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTimeoutInSeconds (seconds As Integer) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithTimeoutInSeconds : int -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IUpdate" Usage="iWithTimeout.WithTimeoutInSeconds seconds" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayProbe.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="seconds" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="seconds">Eine Zahl zwischen 1 und 86400 Sekunden.</param>
        <summary>
            Gibt die Zeitdauer in Sekunden an, das Warten auf eine Antwort, damit der Test ist fehlgeschlagen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>