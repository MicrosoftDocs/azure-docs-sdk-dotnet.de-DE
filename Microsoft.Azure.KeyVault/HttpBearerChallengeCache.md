<Type Name="HttpBearerChallengeCache" FullName="Microsoft.Azure.KeyVault.HttpBearerChallengeCache">
  <TypeSignature Language="C#" Value="public sealed class HttpBearerChallengeCache" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi sealed beforefieldinit HttpBearerChallengeCache extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.KeyVault.HttpBearerChallengeCache" />
  <TypeSignature Language="VB.NET" Value="Public NotInheritable Class HttpBearerChallengeCache" />
  <TypeSignature Language="F#" Value="type HttpBearerChallengeCache = class" />
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
            Singleton-Klasse für die Verarbeitung der HTTP-trägertoken Aufforderung Zwischenspeichern
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Clear">
      <MemberSignature Language="C#" Value="public void Clear ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void Clear() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.HttpBearerChallengeCache.Clear" />
      <MemberSignature Language="VB.NET" Value="Public Sub Clear ()" />
      <MemberSignature Language="F#" Value="member this.Clear : unit -&gt; unit" Usage="httpBearerChallengeCache.Clear " />
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
            Löscht den cache
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetChallengeForURL">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.KeyVault.HttpBearerChallenge GetChallengeForURL (Uri url);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.Azure.KeyVault.HttpBearerChallenge GetChallengeForURL(class System.Uri url) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.HttpBearerChallengeCache.GetChallengeForURL(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetChallengeForURL (url As Uri) As HttpBearerChallenge" />
      <MemberSignature Language="F#" Value="member this.GetChallengeForURL : Uri -&gt; Microsoft.Azure.KeyVault.HttpBearerChallenge" Usage="httpBearerChallengeCache.GetChallengeForURL url" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.HttpBearerChallenge</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="url" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="url"> die URL, die für die Herausforderung zwischengespeichert wird.</param>
        <summary>
            Ruft die Herausforderung für die zwischengespeicherten URL ab.
            </summary>
        <returns>die zwischengespeicherte Herausforderung oder andernfalls Null.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetInstance">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.KeyVault.HttpBearerChallengeCache GetInstance ();" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.KeyVault.HttpBearerChallengeCache GetInstance() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.HttpBearerChallengeCache.GetInstance" />
      <MemberSignature Language="VB.NET" Value="Public Shared Function GetInstance () As HttpBearerChallengeCache" />
      <MemberSignature Language="F#" Value="static member GetInstance : unit -&gt; Microsoft.Azure.KeyVault.HttpBearerChallengeCache" Usage="Microsoft.Azure.KeyVault.HttpBearerChallengeCache.GetInstance " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.KeyVault.HttpBearerChallengeCache</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ruft die Singletoninstanz des<see cref="T:Microsoft.Azure.KeyVault.HttpBearerChallengeCache" /></summary>
        <returns>Instanz dieser Klasse</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoveChallengeForURL">
      <MemberSignature Language="C#" Value="public void RemoveChallengeForURL (Uri url);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void RemoveChallengeForURL(class System.Uri url) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.HttpBearerChallengeCache.RemoveChallengeForURL(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub RemoveChallengeForURL (url As Uri)" />
      <MemberSignature Language="F#" Value="member this.RemoveChallengeForURL : Uri -&gt; unit" Usage="httpBearerChallengeCache.RemoveChallengeForURL url" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="url" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="url"> die URL zum Entfernen der zwischengespeicherten Herausforderung </param>
        <summary>
            Entfernt die zwischengespeicherte Herausforderung für die angegebene URL
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetChallengeForURL">
      <MemberSignature Language="C#" Value="public void SetChallengeForURL (Uri url, Microsoft.Azure.KeyVault.HttpBearerChallenge value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance void SetChallengeForURL(class System.Uri url, class Microsoft.Azure.KeyVault.HttpBearerChallenge value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.KeyVault.HttpBearerChallengeCache.SetChallengeForURL(System.Uri,Microsoft.Azure.KeyVault.HttpBearerChallenge)" />
      <MemberSignature Language="VB.NET" Value="Public Sub SetChallengeForURL (url As Uri, value As HttpBearerChallenge)" />
      <MemberSignature Language="F#" Value="member this.SetChallengeForURL : Uri * Microsoft.Azure.KeyVault.HttpBearerChallenge -&gt; unit" Usage="httpBearerChallengeCache.SetChallengeForURL (url, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.KeyVault</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="url" Type="System.Uri" />
        <Parameter Name="value" Type="Microsoft.Azure.KeyVault.HttpBearerChallenge" />
      </Parameters>
      <Docs>
        <param name="url"> Herausforderung als Cacheschlüssel entsprechende URL </param>
        <param name="value"> Die Herausforderung </param>
        <summary>
            Speichert die Herausforderung für die angegebene URL
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>